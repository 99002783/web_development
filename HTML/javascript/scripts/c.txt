/*var emp={}
emp.empId=123;
emp.empName="charitha"
emp.empAddress="hyderabad"
console.log(emp)
console.log(emp.empId)
console.log(emp.empName)

var emp2=emp;
emp2.empName="vinod";
console.log(emp.empName);*/


let employee =function(id,name,address){
    this.empId=id;
    this.empName=name;
    this.empAddress=address;

    this.display=function(){
        console.log("the name:"+this.empName)
        console.log("the Address:"+this.empAddress)
        console.log("the iD:"+this.empId)
    }
}
let emp1=new employee(123,"vihitha",ap)
let emp2=new employee(124,"vihi",hyd)
emp1.display();
emp1.display();
