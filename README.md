# if-statement
if statement
class ifstatement
{
int a=9,b=7;
void display()
{
int c=a*b;
System.out.println("multiplay of a and b is:"+c);
if(c > 70)
{
	System.out.println("its rite");
}
else if(c > 60)
{
	System.out.println("60 is rite");
}
else
{
	System.out.println("it false");
}
}
void add()
{
String name="jai";
int id=123;
if(id==23)
{
	System.out.println("ok");
}
else
{
	System.out.println("false");
}
System.out.println("name\n"+name+"\nid\n"+id);

}
public static void main(String args[])
{
ifstatement o1=new ifstatement();
o1.display();
o1.add();
}
}
