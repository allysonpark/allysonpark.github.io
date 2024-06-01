<div class="question-area">
    <h4 class="problem-title">
        "Senior class"
    </h4>
    
    <p>
    For each line in the <b>main</b> method of our <b>testPeople</b> class, if something is printed, write it next to the line. If the line results in an error, write next it whether it is a compile time error or runtime error, and then proceed as if that line were not there. 
    
{% highlight java %}
public class Person {
    public String name;
    public int age;

    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }
    
    public void greet(Person other) {
        System.out.println("Hello, " + other.name);
    }
}


public class Grandma extends Person {

    public Grandma(String name, int age) {
        super(name, age);
    }
    
    @Override
    public void greet(Person other) {
        System.out.println("Hello, young whippersnapper");
    }
    
    public void greet(Grandma other) {
        System.out.println("How was bingo, " + other.name + "?");
    }
}

public class testPeople {
    public static void main(String[] args) {
        Person n = new Person("Neil", 12);
        Person a = new Grandma("Ada", 60);
        Grandma v = new Grandma("Vidya", 80);
        Grandma al = new Person("Alex", 70);
        n.greet(a);
        n.greet(v);
        v.greet(a);
        v.greet((Grandma) a);
        a.greet(n);
        a.greet(v);
        ((Grandma) a).greet(v);
        ((Grandma) n).greet(v);
    }
}
{% endhighlight %}
    </p>
</div>