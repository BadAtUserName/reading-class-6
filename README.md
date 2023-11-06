# reading-class-6

Js object basics.<br>
Object Basics<br>
A collection of related data or functionality.<br>
Consists of variables and functions called properties and methonds<br>
	2. Creating an object begins by initializing a variable.,br>
	3. Syntax const person = {}; <br>
	4. Can add more to your object<br>
	— image here****
	
<img width="564" alt="reading 6-1" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/9f6b6ba5-7c61-4597-876c-0077f233dfb5">

5. Can enter things like following into into js<br>
	— image here****

<img width="556" alt="reading 6-2" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/91603dcc-8457-4ab3-acdb-6dc276f7225c">


5. Object made of multiple members each has name age, and val. Each val pair must <bt>
be separated by comma, name and val are separated by colon. Syntax is as follows<br>
	— image here****
 

<img width="546" alt="reading 6-3" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/35b4e88b-71ad-4c22-855b-bd8617786015">

6. Value of object can be anything. In ex we have a num, array 2 functions. <br>
		a) 1st 2 items data items, reffed as objects properties.<br> 
		b). Last 2 items functions allow the object to do something. Reffed as methods<br>

<img width="555" alt="reading 6-4" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/66f0fcf2-970c-4823-8d08-10b1c120048a">

7. Object method functions simpler syntax instead of bio: function() can just write<br>
	bio()<br>
— image here****

<img width="559" alt="reading 6-5" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/ea2df59d-deed-4244-8666-9a949b466864">


8. Object like this reffed as object literal. <br>
		a) written out object contents and what they create. Diff compared to <br> 
		instantiated classes<br>

	b. Common to create object using an object literal you when you want to<br>
  transfer series of structured/ related items. Ex sending a single object more <br>
		efficient <br>
     
     B) Dot notation<br>
	
	1. A way to access objects props and methods.<br> 
		a) write object name (person) aces as namespace must be entered 1st<br>
		b) write a dot. Then item you want to access<br>
		— image here****



<img width="568" alt="reading 6-6" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/813f97ec-ab52-4347-a580-78672b127422">

2. Objects as object properties<br>
		a) object prop can itself be object<br>
		b) to change things like name to name first last need to chain items <br.>
		— image here****

<img width="563" alt="reading 6-7" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/76b86814-1f79-4bb2-814e-55eb6a0baea1">

c) to<br>
		— image here****

<img width="574" alt="reading 6-8" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/d28fb13f-313f-45ff-8091-af1d9f783e86">

d)  to access items you need to chain extra step onto end with another<br> 
		dot. <br>
		—image here****

<img width="557" alt="reading 6-9" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/e970bc30-33f5-41a0-b528-762de1973bed">

e) change method code and any instances of <br>
	— image here****
 
<img width="562" alt="reading 6-10" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/e97723ed-f566-4d70-94f0-8386404eb430">
	
f) to<br> 

<img width="555" alt="reading 6-11" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/6c07cc45-d22d-4ec0-b8df-5c80461aea7e">

C. Bracket Notation<br>
	1. Alt way to access object props instead of dot.<br>
		a). Looks v sims to how to access items in array. Is basically same<br>
		b) instead of using number use name associated with each members<br>
		value. 
	2. Dot notation general pressed over bracket as it is shorter and easier to read<br>

D. Setting object members. <br>
	1. Rather than getting an member/can update value of members using<br>
	dot or bracket notation<br>
<img width="570" alt="reading 6-12" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/ee4d98dc-ca10-423f-959a-7443ad94593a">

2. Change lines to this <br>
	—- image here 13 **
<img width="560" alt="reading 6-13" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/e7db78ac-c32f-4d9c-946e-8a24e7d4d81f">

3. Setting members does note stop at updating values of existing props<br>
	can make all new members<br>
	— image here 14*********

	
<img width="557" alt="reading 6 -14" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/a948cd28-9384-4edf-a7db-6095761f0833">







4. Useful brakes notation can be used to set members val dynamically but also<br>
	member names<br> 
	see following for examples a little over half way down https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics  <br>


E. What is “this” <br>
	1. this  keyword refs to current object the code is being written inside.<br>
		a) handy when you have more than one object literally enables<br> 
		use of same method def for every obj created<br> 
		—-image 15 *****




<img width="578" alt="reading 6-15" src="https://github.com/BadAtUserName/reading-class-6/assets/69227860/0be5d4d7-4e7d-4a5e-b32d-749a1fe3767c">






b) In case person1.introduceSelf() outputs hi I’m Chris<br>
		c) person2.introduces self outputs hi I’m depth. <br>
		d).isn’t super handy when writing them up by hand is handy<br>
		when using constructors<br> 

F.  Intro-ing constructors
	1. Need to create objects repeatedly best to use constructor.<br> 
		a) constructor is just function called using new keyword. <br>
		when calling constructor it will <br>
			1. Create new obj<br>
			2. Bind this to new object to can ref to this in constructor<br>
			3. Run the code in the constructor<br>
			4. Return new object<br>
		b) Constructors start with capital letter are named for the type of<br>
		object they create<br>

G. You’ve been using objects ll along. <br>
	1. Like . Split. .length .join<br>


II. Intro to the DOM <br>
	A. Document object model is the data representation of objects that comprise<br>
	the structure and contend of doc on web<br. 

B. What is the DOM me, it’s me. <br>
		1. Program interface fo web docs. Reps page so programs change doc<br>
		structure<br>
		2. DOM reps doc as nodes and objects the way programming langs<br> 
		can interact with page<br> 
		3. Web page is doc that can be displayed in browser or window as html<br>
		source. 
		4. In both cases it is same dose but DOM rep allows it to be manipulated<br>
		as obj rep of webpage can me model with scripting land such as js<br>
  II. Dom methond

Stuff
Stuff
Stuff
  a. All props methods events avail for manipulation are orged into objects<br>
  b. Dom interface for accessing html table. <br>
 c. OM and JS<br>
  d. Dom is note a programming lang, but w/o it js wouldn’t have any<br>
  e. Model or notion of webpages, html docs, svg docs, etc.

  f.Dom not part of js lang but instead a web api used to build websites.<br>
g. Dom was designed to be independent of any particular programming lang<br>
        i.      Making the structural rep of doc avail from singe consistent api<br>

H. Accessing the DOM<br>
  1. No special instuctons to use dom api in js within script run by browser<br>
  2. When use script elements can immediate use api for the doc or window objects<br>
  3. To manipulate the doc itself.<br>

I. Do not mix structure of page written in html and manipulation of dom (js)<br>
    . Js parts will be grouped together. <br>

J. Fundamental data types. Please see following link to 1/3 page to find table.<br>
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction <br>
K. Dom interfaces
L. Interfaces and objects
  i.      A table object impletments specialed HTMLTAbleElement interface<br>

M Which includes methods as createCaption and insertRow.
 ii.      Also html element table implements the element interface described in<br>

N. Dom element.<br>
iii.      Finally html element is a node in a tree as far as dom cares.<br>

O. Core interfaces of dom<br>
  i. Section about not what the api does but methods and props commonly<br>
  Seen<br>

 ii. The document and window obj are obj whose interfaces gen use most<br>

p. Dom in programming. <br>

1. Window object resps the browser and doc obj is the root of the doc<br>
1. Element inherits from generic node interface<br>
2. Together 2 interface provide props methods used on indie elements<br>
3. Examples please see page for examples https://developer.mozilla.org/en-4. US/docs/Web/API/Document_Object_Model/Introduction <br>
Adding child please see page https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction<br>

	## Stuff I wan to know more about.
  the DOM is confusing. But i'm sure it will make sense after the lecture. 
	







