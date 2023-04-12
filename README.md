
// //program #01
// let num1 =5;
// function add(){
//     let num2 =51
//     return num1 + num2;
// }
// console.log(add());

// //program #02
// let arr =[ "sugar","tea","milk"]
// function myarr(index){
// if(arr.length !== 0){
//     return true ;
// }else {
//     return false;
// }
// }
// console.log(myarr(0));

Program #03
// function Paragraph(text) {
//  let newParagraph =document.createElement("p");
  //newParagraph.textContent = text;
  //document.body.appendChild(newParagraph);
}
// Paragraph("This is a new paragraph!");

// Program #04
// function addItem(text) {
  let Item = document.createElement("li");
  // Item.textContent = text;
 // let list = document.querySelector("ul");
  list.appendChild(Item);
}

// addItem("New list item!");


// // program#06
// let prevStudents=localStorage.getItem("student");
// let students=prevStudents? JSON.parse(prervstudents) :[];
// let student{
//     name: nimra zulfiqar;
//     rollNo; 4444;
// }
// let stringify =JSON stringify(students);
// localStorage.getItem("students",stringify);
    
//program #07

// let myClass = getObject("myKey");
// function getObject(key) {
//     let obj = localStorage.getItem(key);
//     return JSON.parse(obj);
//   }
//   console.log(myClass);

//program #08

// let mymain = {name: "nimra", rollNo: 444};
// let newObject =objectProp(mymain);
// function objectProp(obj) {
//     for (let prop in obj) {
//       localStorage.setItem(prop, JSON.stringify(obj[prop]));
//     }
    
//     let newObj = {};
//     for (const prop in obj) {
//       newObj[prop] = JSON.parse(localStorage.getItem(prop));
//     }
//     return newObj;
//   }
//   console.log(newObject);