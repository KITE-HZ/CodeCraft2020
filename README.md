## ǰ��  
+ **�Ŷ���**����  
+ **�ɼ�**�����۰ĸ���A���2��ȫ����12  
+ **�ֹ�**��  
��1��[KITE-HZ](https://github.com/KITE-HZ "���ϸ�")�е��˴󲿷ֵı�̹������Ż�������Ҳ�����ǵĶӳ���
��2��[Buerzhu](https://github.com/Buerzhu/ "Buerzhu")�е��˶��̵߳��Ż������Ͳ����㷨�Ż�����;
��3��[cxyanhk](https://github.com/cxyanhk "���ϸ�")�е��˲���IO�Ż������Ͳ����㷨�Ż�������

  
##   �Ż�  
+ **�һ��㷨�Ż�**  
��1��������5+2�����ڿ�ʼ�һ�֮ǰ���ȹ���һ��P3���洢·�����������ڵ����Ϣ�� 
��2���ڹ���P3��ʱ��˳���÷����ڽӱ�����P1,P1�һ��ȱ����ӽڵ���Ѱ���Ƿ���ͷ�����һ���ʽ���Ӹ�Ч��
��3����·���еĵ�2��3��4��5ʹ��P3���һ�������ͬʱ����·���ϵ�4��5��6��7�ڵ�ͨ��P1�һ��Ĺ�����
��4���ڷ������3�㹹��P3�Ĺ�����˳��ͳ������Щ�������ľ���С�ڵ���3����������һ����������������м�֦�������������£�  
```cpp
//���ڵ����ĵ㣬����õ�������ľ������3����õ��޻�
if(target.nodeLen[m]!=3 || G[l_it].first <= head || ccm*left<ccL || ccm>right*ccL)
      continue;
```  
  
+ **���ݽṹ�Ż�**
��1��ʹ������������vector���������ݿ�����
��2�����Ƶģ�ʹ��һά�Ͷ�ά�������洢�ڽӱ���P3����Ϣ������������STL������ʹ�ã�
��3���ڽڵ�ȥ�ع������������`sort(temp,temp+sumID)`�У�����temp���ظ��Ľڵ���࣬������������ʱ�䣬���ʹ��һ��`bool idUnique[MAX_ID]`�������洢��Щ�Ѿ���temp�ڵĽڵ㣬�Ӷ������ظ��洢��ͨ������ύ֤�����󲿷ֽڵ�id��С��1�����£�
��4�����Ƶģ���С��1�ڵĽڵ�ʹ���������hashӳ�䣬Ҳ���Լ��ٲ���ӳ��ʱ�䣻
��5����ǰ���ڽӱ�������ٹ��������ڽӱ����Ӷ�ʹ�ú����ڽӱ����򣬼��ٲ�����������
��6��Ϊ�˽�ʡ�ռ��Ѱַʱ�䣬�����㹦�ܵ�����¾���ʹ�ý�С�����ݽṹ�����磬ʹ��uint8_t���洢ÿ���ڵ��Ӧ���ַ������ȣ�
  
+ **���߳��Ż�**
��1��ʹ����ռʽ���ؾ��ⷽʽ���ж��߳��һ���һ������ֿ�Ľڵ���Ϊ100��
��2������atomic_flag�����������������Ա��⻥������ϵͳ���õĿ�����  
��2��ͨ������ύ֤����6�̹߳���Ч���ϼѣ�  
   
+ **�����Ż�**
��1������ʹ�þֲ�������
��2��ʹ��memcpy�����沿�ָ�ֵ������
��3��ʹ��ѭ��չ����
��4�����ü����ϵͳ�Ŀռ�ֲ��Ժ���������ݽṹ��
��5����ȡtxtʹ��mmap;
��6��д��ʹ��fwrite;
��7����if�ж���ע���ж�������˳��
��8����dfs�ݹ��Ϊ���������ٺ������õĿ�����
��9���ò����ʽ�����沿���жϣ�