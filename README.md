########################################
AWR1443 mmWave Demo Դ�������������ע��
########################################

1.��Ҫ�ļ�˵��

main.c
mmWave Demo������

mmw.h
mmWave Demo��ͷ�ļ�������������Ҫ��ͷ�ļ���������Ҫ���ܺ������ṹ��

data_path.c
���ݴ���·�������򣬰�����ADC���ݵ��ռ���1D-FFT��2D-FFT����

config_edma_util.c
ʵ������EDMA���ܵ�API����

config_hwa_util.c
ʵ������FFT��CFARӲ����������API����

mmw_cli.c
ʵ�ֶ�User Port������������в����Ĵ���

post_processing.c
����Ӳ������������FFT��������ݽ���CFAR��⣬��λ�ǡ����ǹ���

sensor_mgmt.c
ʵ�ֶ��״�ǰ�˵Ĺ�������ͨ��CLI������ֹͣ�״�ǰ��

rx_ch_bias_measure.c
ʵ�������������У׼��1.1�汾�¹��ܣ�

mmw.cfg
SYS/BIOSʵʱ�ں˵�RTSC�����������ļ�