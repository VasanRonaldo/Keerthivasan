public class Person {  
   private String name;  
   private int age;  
   
   public Person(String name) {  
      this.name = name;  
      this.age = 18;  
   }  
   
   public Person(String name, int age) {  
      this.name = name;  
      this.age = age;  
   }  
    
   public void displayInfo() {  
      System.out.println("Name: " + name + ", Age: " + age);  
   }  
  
   public static void main(String[] args) {  
      Person person1 = new Person("Teja");  
      person1.displayInfo();
  
      Person person2 = new Person("Appu", 25);  
      person2.displayInfo();
   }  
}
