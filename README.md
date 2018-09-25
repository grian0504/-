# -
9.19 共六題
 /********************************************
         *
         * 我的作業在這裡~~沒按順序~~
         *
         *********************************************/
        /****
         * 這邊是總分跟每科平均
                ****/
//        //這邊我是為了可以分別輸入三組數字
//        Scanner scn = new Scanner(System.in);
//        int v1 = scn.nextInt();
//        Scanner qq = new Scanner(System.in);
//        int v2 = qq.nextInt();
//        Scanner aa = new Scanner(System.in);
//        int v3 = aa.nextInt();
//
//        //這邊是應題目的要求所寫
//        System.out.println("總成績為:\n" + (v1 + v2 +v3));
//        System.out.println("每科平均分數為:\n" + ((v1 + v2 + v3) / 3));

｝｝
        /*****
                * 這邊算的是攝氏轉華氏
                ******/
//        //首先我要讓它可以輸出一組數字
//        Scanner scn = new Scanner(System.in);
//        double v1 = scn.nextDouble();

//        //以下是應題目所寫
//        System.out.println("轉換成華氏後為:\n" + ((v1 * 1.8) + 32));

｝｝
        /****************************
            # float跟double我還是有點搞不清楚差別查一下好了
            *****************************/

        /*******************************************
                * 好，我這邊要算的是兩個整數的合、差及乘積
                ******************************************/
//        //首先我一樣要讓它給我輸入一組數字，因為題目說是整數，所以我用的是int
//        Scanner scn = new Scanner(System.in);
//        int v1 = scn.nextInt();
//
//        //接下來我要再讓它給我輸入一組數字，同樣也是整數，所以是int
//        Scanner qq = new Scanner(System.in);
//        int v2 = qq.nextInt();
//
//        //再來就可以來應題目來寫啦~
//        System.out.println("兩個整數的合為:\n" + (v1 + v2));

｝｝
//
        /**********************
                #這邊有趣的是，差沒有要求的話，通常是大減小，這樣才會是正數或0
            **********************/
//        if ((v1 - v2) >= 0){
//        System.out.println("差為:\n" + (v1 - v2));}
//        else if((v1 - v2 ) < 0){
//            System.out.println("差為:\n" + (v2 - v1));
//         }
//        System.out.println("乘積為:\n" + (v1 * v2));

｝｝
        /******************************************
         * 這邊的題目是身高與體重的換算
         * KG -> 磅
         * CM -> 英吋
         *************************************/
//        //這邊我需要分別輸入兩組數字
//
//        //第一組數字我要輸入的是身高(單位是cm)
//        System.out.println("請先輸入身高(單位為:cm)");
//        Scanner scn = new Scanner(System.in);
//        double v1 = scn.nextDouble();
//
//        //第二組數字我要輸入的是體重(單位是kg)
//        System.out.println("再來輸入的是體重(單位為:kg)");
//        Scanner qq = new Scanner(System.in);
//        double v2 = qq.nextDouble();
//
//        //接下來我要應題目要求來寫啦~
//        System.out.println("身高換算成英吋後為:\n" + (v1 / 2.54));
//        System.out.println("體重換算成磅為:\n" + (v2 / 0.454));

｝｝
/**********
輸入三邊長，確認是否為合法三角形
*******/
Scanner scn = new Scanner(System.in);

double a = scn.nextDouble();

Scanner qq = new Scanner(System.in);

double b = qq.nextDouble();

Scanner aa = new Scanner(System.in);

double c = aa.nextDouble();

if (((a + b) > c) && ((a + c) > b) && ((b + c) > a) && (a <= b && b <= c))
{
System.out.println(“True”);
}

else {
System.out.println(“False”);}

｝｝
/*****
接連輸入三組數字，各自判斷為平年還是閏年
*****/

#以下要先讓我輸入三組數字
Scanner scn = new Scanner(System.in);

int v1 = scn.nextInt();

Scanner qq = new Scanner(System.in);

int v2 = qq.nextInt();

Scanner aa = new Scanner(System.in);

int v3 = aa.nextInt();

#以下要應題目寫出條件

if (((v1 % 4) != 0) || ((v1 % 100) == 0) && ((v1 % 400) != 0));
{
System.out.println(“平年”);
}

else 
{
System.out.println(“閏年”);
}

if (((v2 % 4) != 0) || ((v2 % 100) = 0) && ((v2 %400) != 0));
{
System.out.println(“平年”)
}

else
{
System.out.println(“閏年”)
}

if (((v3 % 4) != 0) || ((v3 % 100) == 0) && ((v3 % 400) != 0));
{
System.out.println(“平年”);
)

else
{
System.out.println(“閏年”)
}


    }}
