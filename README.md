# JS-Notes
All important Notes on javaScript.
<!-- this is var, let and const keywords -->

About the Keywords: var, let and const.

1.Once the variable is declared it connot be alterd.
  ex. you bay a jeans and you go to tailor and make alterd it what size you want.
      like this once you create variable by using this keyword in javascript you will chenge it but it connot br altered.
      
      for ex.
      var myVar = "Hello world";
      myVar[0] = ["j"];
     
2.when javascript variable are declared but not defined by a specific value that mean it has the udefined data types.
      
      for ex.
      var myName;
      here myName has a undefined data type until it get declared by specific values.
      
3.In javascript all variable and function name are case sensitive,this means that capitalization matter.
      for ex. MYNAME  is not same as myName or myname.these all are diffrent meaning in js.
      for this we have to use camalCase in javascript to avoid any vriable declaration mistake.
      
      like. var myVar = "Four";
            var studlyCapVar = "Eight";
            let properCamelCase;
       
4.about the var;
      one of the big problem with var keyword is you can easily override it .
          for ex.
              var myNameIs = "HArshal";
              here i can use again var(myNameIs) to change value in it.
              like
                  var myNameIs = "Surwase";
     you can use declaired variable again.
      it causes problem in big projects.
  
5.about the let keyword.
          once we use the let keyword in code with variable you cannot redeclare it with same variable name in whole project.
          
          for ex. let myName ="Harshal";
                   i cannot redeclare myName variable with let keyword or var or const it cause an error.
                   
              you can reassign the value of the variable.
              like: myName = "Surwase";
                   
              
6.CONST keyword
    const is reffered as read-only keyword.
    const has all the powers that let has.
    but const has speacial power.
    like values are declare using const it is unchanged again.
    for ex.
         const myName = "Harshal";
         myName = "Surwase";
         it cause an error on console.
