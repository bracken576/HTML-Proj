#C++ Inheritance Project

For an inheritance structure in C++ it is important to remember that it is not
the same as it is in java, where you need to have multiple classes or an IDE that
will allow you to run multiple classes from the same file. You can easily run and
should run it from one file. Here is an example below:</p>
class animal{
  public:
    int height;
    int weight;};
class person: public animal{
  public:
    std::string first;
    std::string last;};</a>
int main(void) {
   person pers;
   pers.height = 72; 
   pers.weight = 220;
   pers.last = "Sant"; 
   pers.first = "Bracken"; 
 
   printf("Height: %d   Weight: %d",pers.height, pers.weight);
   cout<<"   Name: "+pers.first+" "+pers.last;
   return 0;
}
  Thus we see that inheritance can be used for many different purposes and can
    be valuable to use in multiple cases. Most importantly it organizes an application
    and makes it easier to run.
