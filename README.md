<!DOCTYPE html>
<html>
<body>

<h1>C++ Inheritance Project</h1>

<p>For an inheritance structure in C++ it is important to remember that it is not<br>
the same as it is in java, where you need to have multiple classes or an IDE that<br>
will allow you to run multiple classes from the same file. You can easily run and<br>
should run it from one file. Here is an example below:</p>
<a><br>class animal{<br>
  &nbsp&nbsp&nbsp&nbsppublic:<br>
    &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspint height;<br>
      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspint weight;<br>};</a>
<a><br><br>class person: public animal{<br>
  &nbsp&nbsp&nbsp&nbsppublic:<br>
    &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspstd::string first;<br>
      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspstd::string last;<br>};</a>
<a><br><br>int main(void) {<br>
   &nbsp&nbsp&nbsp&nbspperson pers;<br>
   &nbsp&nbsp&nbsp&nbsppers.height = 72; <br>
   &nbsp&nbsp&nbsp&nbsppers.weight = 220;<br>
   &nbsp&nbsp&nbsp&nbsppers.last = "Sant";<br> 
   &nbsp&nbsp&nbsp&nbsppers.first = "Bracken"; <br>
 <br>
   &nbsp&nbsp&nbsp&nbspprintf("Height: %d   Weight: %d",pers.height, pers.weight);<br>
  <br>&nbsp&nbsp&nbsp&nbspcout<<"   Name: "+pers.first+" "+pers.last;<br>
   &nbsp&nbsp&nbsp&nbspreturn 0;<br>
}</a>
  <p>Thus we see that inheritance can be used for many different purposes and can<br>
    be valuable to use in multiple cases. Most importantly it organizes an application<br>
    and makes it easier to run.</p>

</body>
</html>
