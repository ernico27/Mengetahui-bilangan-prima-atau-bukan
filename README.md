# Mengetahui-bilangan-prima-atau-bukan

    #include<iostream>
    #include<conio.h>
    using namespace std;
    int main()
    {
    int x,y;
    cout << "\t\t ============================================= \n";
    cout << "\t\t Program pengecekan bilangan prima atau bukan \n";
    cout << "\t\t ============================================= \n";
    cout << "\t\t Masukkan sebuah bilangan : ";
    cin >> x;

    y=0;
    for (int i=1;i<=x;i++)
        if (x%i==0)
        y++;
        if (y==2)
            cout << "\t\t\t\t" << x << " => Bilangan Prima " << endl;
        else
            cout << "\t\t\t\t" << x << " => Bukan Bilangan Prima " << endl;
        return 0;
    }

## Hasilnya

![img](https://github.com/ernico27/Mengetahui-bilangan-prima-atau-bukan/blob/master/bilangan%20prima%201.png?raw=true)

![img](https://github.com/ernico27/Mengetahui-bilangan-prima-atau-bukan/blob/master/bilangan%20prima%202.png?raw=true)
