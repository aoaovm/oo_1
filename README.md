# 邱美萱

## 學號: 0624061

## 資管系 三甲

#### 專題名稱: 

#### 小組成員:


* `0624017 薛日仁`
* 0624061 邱美萱
* 0624027 陳水墻
* 0624073 楊凱勛

###### `My First Assignment`

```
* `0624017 薛日仁`
* 0624061 邱美萱
* 0624027 陳水墻
* 0624073 楊凱勛
```

[高科大](https://www.nkust.edu.tw/)

# My FaceBook
<https://www.facebook.com/profile.php?id=100003718648724>

|First|Second||
|:----|:----:|----:|
|1 |2 |3 |
|1 |2 |3 |

![image](https://github.com/aoaovm/oo_1/blob/master/nkust.png)

abstract class CShape{
  protected String color;
    public void setColor(String str)
{
    color=str;
}
public abstract void show();

}
class CTriangle extends CShape{
    protected double a,b,c;
    public CTriangle(double a,double b,double c){

        this.a=a;
        this.b=b;
        this.c=c;
    }
    public void show(){
      System.out.print("color="+color+", ");
      System.out.println("area="+0.5*a*b);
    }
}

class Main{
    public static void main(String[] args){
        CTriangle triangle =new CTriangle(3,4,5);
        triangle.setColor("Red");
        triangle.show();
    }
}
