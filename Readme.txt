--------------------------HW_1-----------------------
--------------------------HW_03-----------------------
Ū�� (�DCSV�����)

--------------------------HW_04-----------------------
DataFrame���̱`?��������������T��:
float64 �G �B�I�ơA�i��������γs���ܼ�
int64 �G ��ơA�i��������γs���ܼ�
object �G �]�t�r��A�Ω������O���ܼ�

--------------------------HW_05-----------------------
�p���Ƥ����{��: Min�BMax�BRange�BQuartiles�BVar�BStd
�p�ⶰ���Ͷ�
--------------------------HW_06-----------------------
Outlier �γB�z (�����p�H�����, Min, Max �Υ����ƶ��(���ɷ|�� NA))
ø�s���I�� (scatter)�B������ (histogram) �Ψ�L��(boxplot)�ˬd�O�_�����`

--------------------------HW_07-----------------------
�`�Ϊ��ƭȨ��N�G����ƻP����� �s��ƭȼзǤ�
np.quantile�Bnp.median

--------------------------HW_08-----------------------
���s groupby
cut, value_counts
DataFrame����
df.loc[cond, 'col_name']
sub_df = df[['col1','col2']]
plt.boxplot(column=plt_column, by = plt_by)
Z�ഫ: ��Y�N�[��ȻP���饭���Ƥ������Z���A�H�зǮt�����ӭp�� (�зǤ�)
--------------------------HW_09-----------------------
plt.scatter �ݨ��ܼƪ�������
������
�t����
--------------------------HW_10-----------------------
plt.boxplot �ݦ��S��outlier
seaborn.heatmap(�����Y��)
seaborn.pairplot(�����Y��)
--------------------------HW_11-----------------------
�F���ܼƤ������A: Bar & KDE (density plot)
np.linspace
sort_values(by='col_name')['col_name']
seaborn.barplot
seaborn.distplot (������): ���X�Fmatplotlib�� hist()�B�ֱK�ר��kdeplot���\��
--------------------------HW_12-----------------------
�s����������
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
train_Y = �ഫ�᪺label

--------------------------HW_18-----------------------
�`����ƫ��A: float�Bint�Bobject
���A����: type�Bint(var)�Bseries.astype(int)

--------------------------HW_19-----------------------
<�л��w��>
cross_val_score: ��e����

��ɯʥ���
��ɥ�����(Mean) : �ƭȫ����A���A������
�E ��ɤ����(Median) : �ƭȫ����A���A�ܩ���
�E ��ɲ���(Mode) : ���O�����

�ɤ��i��X�{���ƭ� : ���O�����A�����A�X�β��Ʈ�(�g�A������)

�зǤ� / �̤p�̤j�� �ϥΤW���t��
�зǤ� : �ഫ�������췥�ݭȼv�T
�̤p�̤j�� : �ഫ�e�����췥�ݭȼv�T
�ҥH �h�����s�Ȫ��S�x�A����A�M �̤p�̤j��

�D�𪬼ҫ�:  �p�u�ʰj�k, ù�N���j�k, �����g...���A�зǤ� / �̤p�̤j�ƫ��w���|���v�T
�𪬼ҫ� : �p�M����, �H���˪L, ��״��ɾ�...���A�зǤ� / �̤p�̤j�ƫ��w�����|���v�T

�޿�^�k�]Logistic Regression�^�O�����۽u�ʦ^�k�]Linear Regression�^���@���ܧΡC
�u�^�k�v�@��ӻ������O��X�ܶq���s��Ȫ���k�A�ӡu�����v����X�ܶq�O�������]Discrete�^���C
�ҥH��ڤW�A�޿�^�k�O�Ω��������k�A�Ӥ��O�^�k�C

--------------------------HW_20-----------------------
�B�z���p�Ȥ�k:
1. �վ����p�� df['col'].clip(0,2500)
2. �˱����p�� (df['col']> 0) & (df['col']< 2500)

--------------------------HW_21-----------------------
�h�����A:
�~��������A���~�s�����������y�������Ȥ���N���
���O��ƥh���᪺�s�����A�����ȴN����㦳�N���
��ڥh��(sqrt)
�����h��(coxbox) 
��ƥh��(log1p)   

--------------------------HW_22-----------------------
��¦�s�X 1 : ���ҽs�X ( Label Encoding ): �Ӯɤp�C�ǽT���q(�A�ξ𪬼ҫ�)      
��¦�s�X 2 : �W���s�X ( One Hot Encoding ): �Ӯɤj�A�ǽT���@�I(�A�ΫD�𪬼ҫ�)


                           