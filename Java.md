＃原因
####1。帮助开发人员编写代码，提高质量，减少裂缝。一起分析一下突破的构成
#### 2。提升反馈速度，减少重复工作，提升开发效率。
#### 3。保证后续代码修改不会破坏之前的代码的功能
####4。维护代码更容易。
＃###5。有助于改进代码的质量和设计。
'''Java
int s[] = new int[3];
System.out.println("请输入任意三个整数:");
Scanner nn = new Scanner(System.in);
for (int b=0;b < s.length;b++)
    s[b]= nn.nextInt();
for (int i=1;i < 3;i++)
 {
        for (int j=i;j > 0;j--)
       {
            if (s[j] > s[j - 1]) {
            int temp;
            temp=s[j];
            s[j]=s[j-1];
            s[j-1]=temp;
    }
    }

'''
![avatar](https ://s1. ax1x. com/ 2020/09/13/wOvEOs . png)
#测试用例
+第一: 0,1,2,3,4,5,6,7,8,9
+第二: 9,8,7,6,5,4,3,2,1,0
+第三: 5,6,7,1,2,3,8,0,9,4
+第四: 7,5,6,3,2,8,0,9,4,1 
