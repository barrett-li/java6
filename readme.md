JDK 1.6������
�й�JDK1.6��������reamerit�Ĳ��������Ѿ�˵�ĺ���ϸ�ˡ�
 
 
1.Desktop���SystemTray�� 
 
��JDK6�� ,AWT��������������:Desktop��SystemTray�� 
 
ǰ�߿���������ϵͳĬ����������ָ����URL,��ϵͳĬ���ʼ��ͻ��˸�ָ�������䷢�ʼ�,��Ĭ��Ӧ�ó���򿪻�༭�ļ�(����,�ü��±�����txtΪ��׺�����ļ�),��ϵͳĬ�ϵĴ�ӡ����ӡ�ĵ�;���߿���������ϵͳ����������һ�����̳���. 
 
2.ʹ��JAXB2��ʵ�ֶ�����XML֮���ӳ�� 
 
JAXB��Java Architecture for XML Binding����д�����Խ�һ��Java����ת���ΪXML��ʽ����֮��Ȼ�� 
 
�� �ǰѶ������ϵ���ݿ�֮���ӳ���ΪORM, ��ʵҲ���԰Ѷ�����XML֮���ӳ���ΪOXM(Object XML Mapping). ԭ��JAXB��Java EE��һ���֣���JDK6�У�SUN����ŵ���Java SE�У���Ҳ��SUN��һ��������JDK6���Դ������JAXB�汾��2.0, ����1.0(JSR 31)����JAXB2(JSR 222)��JDK5��������Annotation����ʶҪ���󶨵�������Եȣ���ͼ�����˿����Ĺ������� 
 
ʵ ���ϣ���Java EE 5.0�У�EJB��Web ServicesҲͨ��Annotation���򻯿�������������,JAXB2�ڵײ�����StAX(JSR 173)������XML�ĵ�������JAXB֮�⣬���ǻ�����ͨ��XMLBeans��Castor����ʵ��ͬ���Ĺ��ܡ� 
 
3.���StAX 
 
StAX(JSR 173)��JDK6.0�г���DOM��SAX֮�����һ�ִ���XML�ĵ���API�� 
 
StAX ������ ����JAXP1.3(JSR 206)�����ִ���XML�ĵ��ķ���:DOM(Document Object Model)��SAX(Simple API for XML). 
 
�� ��JDK6.0�е�JAXB2(JSR 222)��JAX-WS 2.0(JSR 224)�����õ�StAX����Sun������StAX���뵽JAXP���嵱����������JAXP�İ汾������1.4(JAXP1.4��JAXP1.3��ά���� ��). JDK6����JAXP�İ汾����1.4. �� 
 
StAX��The Streaming API for XML����д��һ��������ģʽ����(pull-parsing)XML�ĵ���API.StAXͨ���ṩһ�ֻ����¼�������(Iterator)��API�� ����Աȥ����xml�ĵ���������,�����������¼�������ȥ����ÿһ�������¼��������¼����Կ����ǳ����������ģ�Ҳ���ǳ����ʹ����������һ�������¼� Ȼ������¼���֮���ִ�ʹ������������һ�������¼������ѭ��ֱ�������ĵ��������� 
SAXҲ�ǻ����¼�����xml�ĵ�����ȴ ������ģʽ����������������������xml�ĵ��󣬲Ų��������¼���Ȼ���Ƹ�����ȥ������Щ�¼���DOM ���õķ�ʽ�ǽ�����xml�ĵ�ӳ�䵽һ���ڴ����������Ϳ��Ժ����׵صõ����ڵ���ӽ���Լ��ֵܽڵ�����ݣ�������ĵ��ܴ󣬽�������Ӱ�����ܡ� 
 
4.ʹ��Compiler API 
 
������ �ǿ�����JDK6 ��Compiler API(JSR 199)ȥ��̬����JavaԴ�ļ���Compiler API��Ϸ��书�ܾͿ���ʵ�ֶ�̬�Ĳ���Java���벢����ִ����Щ���룬�е㶯̬���Ե������� 
 
�� �����Զ���ĳЩ��Ҫ�õ���̬�����Ӧ�ó����൱���ã� ����JSP Web Server���������ֶ��޸�JSP���ǲ�ϣ����Ҫ����Web Server�ſ��Կ���Ч���ģ���ʱ�����ǾͿ�����Compiler API��ʵ�ֶ�̬����JSP�ļ�����Ȼ�����ڵ�JSP Web ServerҲ��֧��JSP�Ȳ���ģ����ڵ�JSP Web Serverͨ���������ڼ�ͨ��Runtime.exec��ProcessBuilder������javac��������룬���ַ�ʽ��Ҫ���ǲ�����һ������ȥ �����빤�����������Ŷ�������ʹ�����������ض��Ĳ���ϵͳ��Compiler APIͨ��һ�����õı�׼��API�ṩ�˸��ӷḻ�ķ�ʽȥ����̬����,�����ǿ�ƽ̨�ġ� 
 
5.������Http Server API 
 
JDK6 �ṩ��һ���򵥵�Http Server API,�ݴ����ǿ��Թ����Լ���Ƕ��ʽHttp Server,��֧��Http��HttpsЭ��,�ṩ��HTTP1.1�Ĳ���ʵ�֣�û�б�ʵ�ֵ��ǲ��ֿ���ͨ����չ���е�Http Server API��ʵ��,����Ա�����Լ�ʵ��HttpHandler�ӿ�,HttpServer�����HttpHandlerʵ����Ļص�����������ͻ�������,�� ����,���ǰ�һ��Http�����������Ӧ��Ϊһ������,��װ��HttpExchange��,HttpServer����HttpExchange���� HttpHandlerʵ����Ļص�����. 
 
6.����ʽע�⴦��API(Pluggable Annotation Processing API) 
 
����ʽע�⴦��API(JSR 269)�ṩһ�ױ�׼API������Annotations(JSR 175) 
 
ʵ ����JSR 269��������������Annotation,�Ҿ��ø�ǿ��Ĺ�������������Java ���Ա����һ��ģ��,����method, package, constructor, type, variable, enum, annotation��Java����Ԫ��ӳ��ΪTypes��Elements(������ʲô����?), �Ӷ���Java���Ե�����ӳ���Ϊ����, ���ǿ�����javax.lang.model��������Կ�����Щ��. �������ǿ�������JSR 269�ṩ��API������һ�����ܷḻ��Ԫ���(metaprogramming)����. 
 
JSR 269��Annotation Processor�ڱ����ڼ�����������ڼ䴦��Annotation, Annotation Processor�൱�ڱ�������һ�����,���Գ�Ϊ����ʽע�⴦��.���Annotation Processor����Annotationʱ(ִ��process����)�������µ�Java����,���������ٵ���һ��Annotation Processor,����ڶ��δ������´������,�ͻ���ŵ���Annotation Processor,ֱ��û���´������Ϊֹ.ÿִ��һ��process()��������Ϊһ��"round",��������Annotation processing���̿��Կ�����һ��round������. 
 
JSR 269��Ҫ����Ƴ�Ϊ���Tools����������API. �ٸ�����,�����뽨��һ�׻���Annotation�ĵ�Ԫ���Կ��(��TestNG),�ڲ�����������Annotation����ʶ�����ڼ���Ҫִ�еĲ��Է����� 
 
7.��Console��������̨���� 
 
JDK6 ���ṩ��java.io.Console ��ר�������ʻ����ַ��Ŀ���̨�豸. ��ĳ������Ҫ��Windows�µ�cmd����Linux�µ�Terminal����,�Ϳ�����Console�����. �����ǲ������ܵõ����õ�Console, һ��JVM�Ƿ��п��õ�Console�����ڵײ�ƽ̨��JVM��α�����. ���JVM���ڽ���ʽ������(����Windows��cmd)��������,�����������û���ض�������ĵط�,��ô�Ϳ��Եõ�һ�����õ�Consoleʵ ��. 
 
8.�Խű����Ե�֧����: ruby, groovy, javascript. 
 
9.Common Annotations 
 
Common annotationsԭ����Java EE 5.0(JSR 244)�淶��һ���֣�����SUN������һ���ַŵ���Java SE 6.0��. 
�� ��AnnotationԪ���ݹ���(JSR 175)���뵽Java SE 5.0���棬�ܶ�Java ����(����EJB,Web Services)������Annotation���ִ���XML�ļ����������в���������˵��֧������ʽ���,��EJB������ʽ����, �����Щ����Ϊͨ��Ŀ�Ķ������������Լ���Annotations,��Ȼ�е��ظ�����, ����,Ϊ������ص�Java��������һ�׹�����Annotation���м�ֵ�ģ����Ա����ظ������ͬʱ��Ҳ��֤Java SE��Java EE ���ּ�����һ����. 
 
�����оٳ�Common Annotations 1.0�����10��Annotations Common Annotations 
Annotation Retention Target Description 
Generated Source ANNOTATION_TYPE, CONSTRUCTOR, FIELD, LOCAL_VARIABLE, METHOD, PACKAGE, PARAMETER, TYPE ���ڱ�ע���ɵ�Դ���� 
Resource Runtime TYPE, METHOD, FIELD ���ڱ�ע����������Դ,�����ݴ�ע���ⲿ��Դ�������л����ֶε�ע��ͻ���setter������ע�����ַ�ʽ 
Resources Runtime TYPE ͬʱ��ע����ⲿ�������������������Щ�ⲿ����ע�� 
PostConstruct Runtime METHOD ��ע������ע����������֮�����еķ�����������������ע���ĳ�ʼ��������ֻ��һ���������Ա�עΪPostConstruct 
PreDestroy Runtime METHOD ������ʵ����Ҫ������������ɾ��֮ǰ��Ҫִ�еĻص�����Ҫ��עΪPreDestroy RunAs Runtime TYPE ���ڱ�ע��ʲô��ȫ��ɫ��ִ�б���ע��ķ����������ȫ��ɫ�����Container ��Security��ɫһ�µġ�RolesAllowed Runtime TYPE, METHOD ���ڱ�ע����ִ�б���ע��򷽷��İ�ȫ��ɫ�������ȫ��ɫ�����Container ��Security��ɫһ�µ� 
PermitAll Runtime TYPE, METHOD �������н�ɫִ�б���ע����򷽷� 
DenyAll Runtime TYPE, METHOD �������κν�ɫִ�б���ע����򷽷�����������򷽷�������Java EE������������ 
DeclareRoles Runtime TYPE ����������Ա�Ӧ�ó������İ�ȫ��ɫ��ͨ����isUserInRole�����鰲ȫ��ɫ 
 
ע��: 
1.RolesAllowed,PermitAll,DenyAll����ͬʱӦ�õ�һ����򷽷��� 
 
2.��ע�ڷ����ϵ�RolesAllowed,PermitAll,DenyAll�Ḳ�Ǳ�ע�����ϵ�RolesAllowed,PermitAll,DenyAll 
 
3.RunAs,RolesAllowed,PermitAll,DenyAll��DeclareRoles��û�мӵ�Java SE 6.0���� 
 
4. ��������Annotations�Ĺ�������Java EE��������, Java SE 6.0ֻ�ǰ������������ǰ����Annotations�Ķ�����,��û�а���������ЩAnnotations������,�������������Pluggable Annotation Processing API(JSR 269)����
 
 
 
�Ķ��ĵط����ľ���java GUI�������ʾ�ˣ�JDK6.0��Ҳ����JDK1.6��֧�����µ�windows vistaϵͳ��Windows Aero�Ӵ�Ч������JDK1.5��֧�֣����� 
��Ҫ��vista�����±�̵Ļ����װjdk6.0�����������ǻ���windows basic�Ӵ�Ч��.

����Ҫ�ĸĽ�����3�㣺
���ǻ�û�и�������ǵ�ʵ�����壬��������Ŀ������ʲô����

����ʽע�⴦��API(Pluggable Annotation Processing API)
����ʽע�⴦��API(JSR 269)�ṩһ�ױ�׼API������Annotations(JSR 175)
ʵ����JSR 269��������������Annotation,�Ҿ��ø�ǿ��Ĺ�������������Java ���Ա����һ��ģ��,����method,package,constructor,type,variable, enum,annotation��Java����Ԫ��ӳ��ΪTypes��Elements(������ʲô����?),�Ӷ���Java���Ե�����ӳ���Ϊ����,�� �ǿ�����javax.lang.model��������Կ�����Щ��. ���ǿ�������JSR 269�ṩ��API������һ�����ܷḻ��Ԫ���(metaprogramming)����.
JSR 269��Annotation Processor�ڱ����ڼ�����������ڼ䴦��Annotation,Annotation Processor�൱�ڱ�������һ�����,��Ϊ����ʽע�⴦��.���Annotation Processor����Annotationʱ(ִ��process����)�������µ�Java����,���������ٵ���һ��Annotation Processor,����ڶ��δ������´������,�ͻ���ŵ���Annotation Processor,ֱ��û���´������Ϊֹ.ÿִ��һ��process()��������Ϊһ��"round",��������Annotation processing���̿��Կ�����һ��round������.
JSR 269��Ҫ����Ƴ�Ϊ���Tools����������API. �ٸ�����,�����뽨��һ�׻���Annotation�ĵ�Ԫ���Կ��(��TestNG),�ڲ�����������Annotation����ʶ�����ڼ���Ҫִ�еĲ��Է���.

�Խű����Ե�֧��
�磺 ruby,groovy,javascript

Common Annotations
Common annotationsԭ����Java EE 5.0(JSR 244)�淶��һ���֣�����SUN������һ���ַŵ���Java SE 6.0��. 
�� ��AnnotationԪ���ݹ���(JSR 175)���뵽Java SE 5.0���棬�ܶ�Java ����(����EJB,Web Services)������Annotation���ִ���XML�ļ����������в���������˵��֧������ʽ���,��EJB������ʽ����, �����Щ����Ϊͨ��Ŀ�Ķ������������Լ���Annotations,��Ȼ�е��ظ�����, ����,Ϊ������ص�Java��������һ�׹�����Annotation���м�ֵ�ģ����Ա����ظ������ͬʱ��Ҳ��֤Java SE��Java EE ���ּ�����һ����. 
 
�����оٳ�Common Annotations 1.0�����10��Annotations Common Annotations 
Annotation Retention Target Description 
Generated Source ANNOTATION_TYPE, CONSTRUCTOR, FIELD, LOCAL_VARIABLE, METHOD, PACKAGE, PARAMETER, TYPE ���ڱ�ע���ɵ�Դ���� 
Resource Runtime TYPE, METHOD, FIELD ���ڱ�ע����������Դ,�����ݴ�ע���ⲿ��Դ�������л����ֶε�ע��ͻ���setter������ע�����ַ�ʽ 
Resources Runtime TYPE ͬʱ��ע����ⲿ�������������������Щ�ⲿ����ע�� 
PostConstruct Runtime METHOD ��ע������ע����������֮�����еķ�����������������ע���ĳ�ʼ��������ֻ��һ���������Ա�עΪPostConstruct 
PreDestroy Runtime METHOD ������ʵ����Ҫ������������ɾ��֮ǰ��Ҫִ�еĻص�����Ҫ��עΪPreDestroy RunAs Runtime TYPE ���ڱ�ע��ʲô��ȫ��ɫ��ִ�б���ע��ķ����������ȫ��ɫ�����Container ��Security��ɫһ�µġ�RolesAllowed Runtime TYPE, METHOD ���ڱ�ע����ִ�б���ע��򷽷��İ�ȫ��ɫ�������ȫ��ɫ�����Container ��Security��ɫһ�µ� 
PermitAll Runtime TYPE, METHOD �������н�ɫִ�б���ע����򷽷� 
DenyAll Runtime TYPE, METHOD �������κν�ɫִ�б���ע����򷽷�����������򷽷�������Java EE������������ 
DeclareRoles Runtime TYPE ����������Ա�Ӧ�ó������İ�ȫ��ɫ��ͨ����isUserInRole�����鰲ȫ��ɫ 
 
ע��: 
1.RolesAllowed,PermitAll,DenyAll����ͬʱӦ�õ�һ����򷽷��� 
 
2.��ע�ڷ����ϵ�RolesAllowed,PermitAll,DenyAll�Ḳ�Ǳ�ע�����ϵ�RolesAllowed,PermitAll,DenyAll 
 
3.RunAs,RolesAllowed,PermitAll,DenyAll��DeclareRoles��û�мӵ�Java SE 6.0���� 
 
4. ��������Annotations�Ĺ�������Java EE��������, Java SE 6.0ֻ�ǰ������������ǰ����Annotations�Ķ�����,��û�а���������ЩAnnotations������,�������������Pluggable Annotation Processing API(JSR 269)����