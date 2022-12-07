### Hi there 👋

* 🔭 I´m currently learning Dart, Java and MySQL
* 📩 Ask me about anything related to Java/JavaScript
* 📫How to reach me: fernandodj2004@gmail.com
* 😃 Fun fact: I ♥️ movies

```java
package aboutMe;
import java.util.ArrayList;

public class Me {

  private String name, lastName;
  private int age;
  public ArrayList<String> tools = new ArrayList<>();;
  
  public Me(String name, String lastName, int age) {
    this.name = name;
    this.lastName = lastName;
    this.age = age; 
  }
  
  @Override
  public String toString() {
    return "Me{" + "name='" + name + '\'' + ", lastName='" + lastName + '\'' + ", age=" + age + ", tools =" + tools + '}';
  }
  
  public static void main(String[] args) {
    Me diego = new Me("Diego Fernando", "Mueses Zuñiga", 18);
    diego.tools.add("HTML");
    diego.tools.add("CSS");
    diego.tools.add("JS");
    diego.tools.add("Java");
    System.out.println(diego.toString());
  }

}
```
> Console
```
Me{name='Diego Fernando', lastName='Mueses Zuñiga', age=18, tools =[HTML, CSS, JS, Java]}
```
