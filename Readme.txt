--------------------------HW_1-----------------------
--------------------------HW_03-----------------------
讀檔 (非CSV的資料)

--------------------------HW_04-----------------------
DataFrame中最常?的欄位資料類型有三種:
float64 ： 浮點數，可表示離散或連續變數
int64 ： 整數，可表示離散或連續變數
object ： 包含字串，用於表示類別型變數

--------------------------HW_05-----------------------
計算資料分散程度: Min、Max、Range、Quartiles、Var、Std
計算集中趨勢
--------------------------HW_06-----------------------
Outlier 及處理 (視情況以中位數, Min, Max 或平均數填補(有時會用 NA))
繪製散點圖 (scatter)、分布圖 (histogram) 或其他圖(boxplot)檢查是否有異常

--------------------------HW_07-----------------------
常用的數值取代：中位數與分位數 連續數值標準化
np.quantile、np.median

--------------------------HW_08-----------------------
分群 groupby
cut, value_counts
DataFrame應用
df.loc[cond, 'col_name']
sub_df = df[['col1','col2']]
plt.boxplot(column=plt_column, by = plt_by)
Z轉換: 亦即將觀察值與母體平均數之間的距離，以標準差為單位來計算 (標準化)
--------------------------HW_09-----------------------
plt.scatter 看兩變數的相關性
正相關
負相關
--------------------------HW_10-----------------------
plt.boxplot 看有沒有outlier
seaborn.heatmap(相關係數)
seaborn.pairplot(相關係數)
--------------------------HW_11-----------------------
了解變數分布狀態: Bar & KDE (density plot)
np.linspace
sort_values(by='col_name')['col_name']
seaborn.barplot
seaborn.distplot (分布圖): 集合了matplotlib的 hist()、核密度函數kdeplot的功能
--------------------------HW_12-----------------------
連續資料離散化
cut, qcut, value_counts

--------------------------HW_13-----------------------
seaborn.catplot

--------------------------HW_14-----------------------
subplot
warnings.filterwarnings
np.sort
cut, groupby

--------------------------HW_15-----------------------
rand, randint, uniform, randn, normal

seaborn.heatmap
seaborn.PairGrid
kdeplot
--------------------------HW_16-----------------------
Imputer
MinMaxScaler
Fit the model
LogisticRegression
--------------------------HW_17-----------------------
LinearRegression.fit(train_X, train_Y)
train_Y = 轉換後的label