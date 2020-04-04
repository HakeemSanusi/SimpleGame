# SimpleGame
The first code 
public Class Temperature{
  public static void main(String[] args){
  double conversion;
    Scanner input = new Scanner(System.in);
    System.out.println("What is the value you wanted to convert ");
    int value = input.nextInt();
    System.out.println("What is your choice \n Kelvin or Celsius ");
    String choice = input.next();
    if (choice.equals("Celsius"){
      conversion = 273 - value ;
      System.out.println("The conveted value in celsius is " + conversion);
    }
    esle if (choice.equals("Kelvin"){
      conversion = 273 + value;
      System.out.println("The converted value to kelvin is " + conversion);
    }
    else{
      System.out.println("Enter the correct value \n Run the program again");
