## Intro
This is another tool helping to generate c file for dll hijack, besides AheadLib and AddExport.

���� AheadLib �� AddExport ֮��ģ���һ������ DLL �ٳ� C Դ����ĸ������ߡ�

It is fully based on the function forwarding feature of the MSVC linker.

����ȫʹ�� MSVC linker �� DLL �����ض������ԡ�

It's coded in python for easier change of the c file template.

ʹ�� python ��Ϊ�˱����޸����ɵĴ��롣

There are 2 tricks on the c files: 1, implement some functions yourself; 2, sideload extra codes by the dll entry.

����������� 2 ����1���Լ�ʵ��Ҫ�޸ĵĺ�����2���� dll ��ڣ���·�����ض���Ĵ��롣

homepage: https://github.com/lifenjoiner/hijackdll_helper

AheadLib: https://github.com/Yonsm/AheadLib, https://github.com/strivexjun/AheadLib-x86-x64

AddExport: https://bbs.pediy.com/thread-154269.htm

## Dependencies
python3

pefile
