# 111
#include <iostream>
#include <cstdio>
bool marks[28];
int main(){
    marks['a'-'a']=marks['e'-'a']=marks['i'-'a']=marks['o'-'a']=marks['u'-'a']=true;
    printf("请输入字母：");
    char ch=getchar();
    if(ch<='Z') ch+=32;
    printf("%s",marks[ch-'a']?"是元音":"是辅音");
    return 0;
}
