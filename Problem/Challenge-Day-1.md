# [Frontend Lab 1](https://codedamn.com/problem/WsP0htQRj3T8pGWNmTiXQ?challengeList=100-days-of-frontend)

### **Semantic HTML Structure**

> **_Welcome to HTML Basic Semantic Layout Lab , In this lab, you'll create a very simple html page layout that would contain four semantic html elements.
> This challenge is focused on helping you understand the basic layout of any website that is created. Take a look at the challenges, for clear break down of tasks
> that you have to accomplish in this lab._**

# Challenge 1

### **Challenge**

> **_First start by creating an empty div and give it an id with text container , we'll write our entire HTML content inside this container then Create a header element and add the text 'Page Header'._**

---

**Solution for the challenge**

```html
<div id="container">
    <header>Page Header</header>
<div>
```


# Challenge 2 

### **Challenge**

> **_Create a navigation bar using 'nav' tag which contains a list of links using the list (li) element inside navbar using an unordered list ('ul' tag). You can add your favourite links inside the li elements._**

---

**Solution for the challenge**

```html
<nav>
	<ul>
		<li><a href="#">Home</a></li>
		<li><a href="#">About</a></li>
		<li><a href="#">Services</a></li>
		<li><a href="#">Contact</a></li>
	</ul>
</nav>
```

# Challenge 3

### **Challenge**

> **_Create a main content area using 'main' tag which occupies the remaining space after header and nav elements._**

---

**Solution for the challenge**

```html
<main>Main Content</main>
```

# Challenge 4

### **Challenge**

> **_Create a footer element and the text 'Footer' inside it._**

---

**Solution for the challenge**

```html
<footer>Footer</footer>
```

---

### **Initial Code for the Lab**

```html
<!DOCTYPE html>
<html>
	<head>
		<title>Semantic HTML Structure</title>
		<link rel="stylesheet" href="style.css" />
	</head>
	<body>
		<!-- Starting writing your code below this line -->
	</body>
</html>

```

### **Final Code for the Lab**

```html
<!DOCTYPE html>
<html>
	<head>
		<title>Semantic HTML Structure</title>
		<link rel="stylesheet" href="style.css" />
	</head>
	<body>
		<!-- Starting writing your code below this line -->
		<div id="container">
			<header>Page Header</header>
			<nav>
				<ul>
				  <li><a href="#">Home</a></li>
				  <li><a href="#">About</a></li>
				  <li><a href="#">Services</a></li>
				  <li><a href="#">Contact</a></li>
				</ul>
			  </nav>
			  <main>Main Content</main>
			  <footer>Footer</footer>
		</div>

	</body>
</html>

```

## Conclusion

**_These was the solved problems of day 1._**

[**_Link to the lab_**](https://codedamn.com/problem/WsP0htQRj3T8pGWNmTiXQ?challengeList=100-days-of-frontend "Next Day")

[**_Go to next day_**](https://github.com/h4ckibl3/100-Days-of-Frontend/blob/main/Problem/Challenge-Day-2.md "Next Day")








