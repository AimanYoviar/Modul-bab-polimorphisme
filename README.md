# Modul-bab-polimorphisme

Latihan 1

![Screenshot (224)](https://user-images.githubusercontent.com/68726545/115817894-de953e00-a425-11eb-990f-dbe0b189bb96.png)

Latihan 3

![Screenshot (225)](https://user-images.githubusercontent.com/68726545/115817986-071d3800-a426-11eb-9254-b7200b73087a.png)

Latihan4

![Screenshot (226)](https://user-images.githubusercontent.com/68726545/115818050-1ef4bc00-a426-11eb-9968-b8121cb8dd24.png)


Latihan2.1

    public interface Relation {
    public boolean isGreater(Object a, Object b);
    public boolean isLess(Object a, Object b);
    public boolean isEqual(Object a, Object b);
    }

Latihan 2.2

    class Line implements Relation {
    private double x1;
    private double x2;
    private double y1;
    private double y2;
    
    public Line(double x1, double x2, double y1, double y2);
    this.x1=x1;
    this.x2=x2;
    this.y1=y1;
    this.y2=y2;
 
     }
         public double getLength(){
     double length=Math.sqrt((x2-x1)*(x2-x1)+(y2-y1)*(y2-y1));
     return length;
     }
     public boolean isGreater(Object a, Object b){
    double aLen=((Line)a).getLength();
    double bLen=((Line)b).getLength();
     return (aLen>bLen);

     }
     public boolean isGreater(Object a, Object b){
     double aLen=((Line)a).getLength();
     double bLen=((Line)b).getLength();
     return (aLen<bLen);
    }
    public boolean isGreater(Object a, Object b){
    double aLen=((Line)a).getLength();
    double bLen=((Line)b).getLength();
    return (aLe==bLen);
    }  
    }
