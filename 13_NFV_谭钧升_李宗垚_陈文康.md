#The Click Modular Router

##�����ṩ�Ŀ���
1. ΪʲôҪ�������������봫ͳ������
	Unfortunately, most routers have closed, static, and inflexible designs. ���еĴ����·��������ƶ��Ƿ�յģ���̬�ĺͿ̰�ġ�
    Network administrators may be able to turn router functions on or off, but they cannot easily specify or even identify the interactions of different functions.
    �������Ա����ָ���������岻ͬfunctions֮��Ľ�����
    Furthermore, network administrators and third  party software vendors cannot easily implement new  functions.
    ���ң�Ҫʵ���µ�functions���ѡ�
    �봫ͳ�����𣺣�1�����:����������µĹ��� ��2����ģ�黯��ͨ�����Ԫ����ʵ�ֹ��ܣ� ��3���� Open�������������Ԫ�أ�Elements);��4����Ч�ʣ���Ӳ����������

2. Pull��Push
	push��pull��Click��elementsֱ�ӵ��������ӷ�ʽ��
	Push�Ǵ�ԴElement�����ε�Ԫ�أ�ͨ���¼������������а������Push���ӷ�ʽ����ε�Ԫ�ػ��ύһ���������ε�Ԫ�أ�
    Pull�Ǵ�Ŀ�ĵ�Ԫ�ص�����Ԫ�ء���Pull�����ӷ�ʽ������ε�Ԫ�ط��Ͱ��������ε�Ԫ�ء�������ӿ�׼���÷���ʱ���Ὺʼһ��pull���̣��ù��̻�һֱ������ͼֱ������ĳ��Ԫ�ء��³���һ������

3. ������
	��Click�����������һ�����Ŷ������˿ڣ�һ������˿ڵ�pull element��
	��ͨ��һ���ĵ��Ȳ���������������input�����İ�Ӧ����ι������Output��
	���������ᵽclickʵ����������������Round-Robin Sched �� PrioSched (Priority Scheduler)�� Round-Robin Sched ���Ƕ�input������ѯ�� PrioSched (Priority Scheduler)����ÿ�ζ��ӵ�һ��input��ʼpull packets��
	
4. Dropping Policies
	Clickͨ������Ԫ����ʵ��һ���򵥵�Dropping���ԣ� Ҳ���ǵ�����Ŀ�������õ���󳤶�ʱ����Щ�����ᱻ�ӵ���
	�����ᵽ��Dropping���ԣ���1����RED��Random Early Detection�� ��Element�����ε�����Ķ��г�����ΪDropping�����ݡ�(2), RED over multiple queues: ���RED�������ж�����У��Ǿͽ���Щ���еĳ��ȶ���������ΪDropping�����ݣ���3����weight RED: ÿ���������������ȼ��в�ͬ��Drop�ĸ��ʡ�
	
5. NFV:Network Function Virtualization
   Network Functions(Middleboxes): Firewall, IDS, DNS�����繦�����⻯�������⻯��Щ���繦�ܣ�Ҳ����ͨ�����ģ��ʵ����Щ���繦�ܡ�
   ����˵�ǣ�����������ʩ���������
    NFVĿ�꣺��1��ʡǮ��ʹ�ø����˵���ҵ��������ʵ�����繦�ܣ�����ר��Ӳ����ʹ�ã��Ӷ������ܺģ������ܹ������ά������2��׬Ǯ���������������
    ���������ʩ��Ϊ����


##���

##�κ�����

