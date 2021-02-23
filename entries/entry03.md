# Entry 3
##### 02/17/2021

Since my last blog entry, I have learned how to analyze code and understand the process behind each user when they sign in and sign out. I have continued to work on and experiment using a codelab Firebase did a couple of months ago. I have also looked over a variety of websites and YouTube videos to get a bigger understanding of Firebase, and it finally stuck to me how Firebase really works.

In the past, I had learned how Firebase was a Backend-as-a-Service (BaaS), but I guess I never really understood what it actually meant. However, after looking through videos and articles, I have found out that you can essentially create any web app and then host it using Google's Firebase as a hosting site. This made me want to create a Bootstrap Website to then deploy using Firebase, but after much research, I realized that it wasn't going to be that easy. After seeing videos like, [Firebase - Back to the Basics](https://www.youtube.com/watch?v=q5J5ho7YUhA), [Fast React Website Deployment With Firebase](https://www.youtube.com/watch?v=IDHfvpsYShs), [4 Setup bootstrap and firebase](https://www.youtube.com/watch?v=lrYlH3LGswo),  I learned how users can get started with Firebase and how they can take different approaches. Some had used Bootstrap, others had used React, but in the end they ended up using Firebase to host their website. In particular for my project, I was finally able to make the user sign in and submit a goal they have for the day. What was interesting to see was how if the user signs out, they wouldn't lose any goals they typed in before signing out of their account.

Code Snippets 
`
<body>

	<div id="app">
		<!-- image of water  -->
		<img
      src="https://post.greatist.com/wp-content/uploads/sites/2/2019/08/GRT-still-life-drinking-water-glass-1200x628-facebook.jpg"
    />

		<div id="app">
			<!-- image of water  -->
			<img
      src="https://post.greatist.com/wp-content/uploads/2020/08/11178-Different_types_of_water_facebook-1200x628-1-1200x628.jpg"
    />

	<section id="event-details-container">
		<h1>keepHydrated</h1>
		<h4><i> keep yourself hydrated </i></h4>

		<p><i class="material-icons">calendar_today</i> February 17, 2021</p>
		<!-- <p><i class="material-icons">location_city</i> Ne</p> -->
		<button id="startRsvp">Sign In</button>

		</section>

		<hr>

		<section id="firebaseui-auth-container"></section>

		<section id="description-container">
			<h2>Create an account to sign in and track your daily intake of water!</h2>

  		<h2>Goals</h2>

		<form id="leave-message">
			<label>What goal do you have for today? </label>
			<input type="text" id="message">
			<button type="submit">
		       <i class="material-icons">send</i>
		       <span>Submit</span>
		     </button>
						</form>	`


![Screenshot of Web App](https://github.com/jazminn7822/apcsa-freedom-project/blob/master/entries/Main%20Screen.png){:target="_blank"}
![Screenshot of Web App](https://github.com/jazminn7822/apcsa-freedom-project/blob/master/entries/Sign%20In.png)
![Screenshot of Web App](https://github.com/jazminn7822/apcsa-freedom-project/blob/master/entries/Logged%20In.png)
![Screenshot of Web App](https://github.com/jazminn7822/apcsa-freedom-project/blob/master/entries/Logged%20In%202.png)

Somethings that I have been learning in class that apply directly to my project is the content from the units. For every unit we have coding activites, which is similar to what I am doing now. I am doing and learning from coding activities that Firebase goes through in their videos. In regards to the **Engineering Design Process**, I am in Step 3 and Step 4, Brainstorming possible solutions and
Planning the most promising solution. I am continuing to brainstorm by doing research and understanding where exactly I need to begin from whether it's creating a bootstrap website and then using Firebase to host it or take a different approach. I am also continung to brainstrom how I want my web app to look like as I want it to be efficient to users. Some of the **skills** I have developed along the way are (1)How to read and (2)Embracing failure. I have come across the uncertainty of not knowing what steps to take next, but using Google and analyzing documentations or other sources carefully has definitely helped me learn and find out what to do next. For now, I will continue to do more research and try to advance more in the making of my web app. 

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
