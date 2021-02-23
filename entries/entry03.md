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


![Web Image](https://gm1.ggpht.com/zxPgXCXmal050NRv8OecWA7FrYZdtVwh69ETmcRcHFyTz1yzLcBsAokrV2yP1kBls2iTTzyPQYdlPuWwsk5EoFrSdhc1mARAw2bMLYp1mcXXy2EwN3cG1j8wzRIN4g4Ui-XJGIvJeREkZLBV7-8crmcTLi50ZdjWhATslLivYmR4hpHXghBG4eMB-3mOArn34p0D5hGNbHYrcMnPWGwTHYlMhGXkuCYltS-y2lp_rbeFaun59cVdYTbjsnZWqlKG8Kk6l3bYP1dB2TyV-XKY4XH3geF3Rz2_hQmEr0kFdm-B2bNAbxf0ywav0tPUAn7W9mQs_yWtRgg15jpRyTa1avSk4FD5GaPvx58DYXB238t_s5X9jqKZpqobvriK9-mo4fXAECwvYFcPWv3ZlFMWkuMCBY0GgUXiuW-zQyKYBgFFuGPsFObZXZ0lJly24JTBhPkKrn_IZQfbjlDOjwBeeYYTihj7VMgBlErcdq3lXPGCBg9F52dgmcFcY0kNAQvxjqTDO6ED25fWLP1S2CVhYarKLs6oVfVtchi03eV4dmnIsnl8106v48fbTnG4qUJtrV-Z6r4SExDlDro6NTBrymEy0aDZV7uRzvxnpThvhJapserei5CGFcIetKgLX_WR4m01_iteB1gQGxUVyQzSQMT0H4-VZ1yNxUwqxkTeOTxhxT6SvV965YZLLZMKnQ2SKYE2u4r-L8CNOzonNCDsOt4twFJ2-WMuP4mjJyNLSvGMo18vsbFEGz0UJt7qmO_Zj94j=s0-l75-ft-l75-ft)

![Web Image]((https://gm1.ggpht.com/XofM10-23gmuxsml4eQzzShrms6oSf53v1KSKUOTKk5elMchhRiSecEXXoH5XFfDRnMKG2bu-EVg8ARVoSCQ_8XV4j6RUmRZmu0MOXSxeMunVcwwNQD1mOzSP796vgqQ3Ue4on-X74-6oSy-DNYFgvTxLgJhzuEZmBWvTod-047XpcqNdBnfEMBWgBHKfOb15aVdr4oq37T_HsqtesmTTFyFwMAqvyBE-fjcmTM0EvIt11HwjbBV2vsWbSpHe7Y7UM82UmMHu-ouVVvjZbCYSOanzwli94KMzuDlyUboTDb8QvNQn7HnNltMiQr5Y3Xf7u00Ou9SqlTPgnY5ajJjmCXQNDHYi8YlNEgFUW5mWDWf8TDJL-6INDfLrMh1LHinDNpBaN12GvzVQJwqD9Won-VI6ETUyLUBp89Mxf0tKH5nJho1uX7KN5RVfK1pZlPIRlrYzYHL8JM9bOzJbzeVqs6FXV-majKHzUmmvfkClrVYpvdLML8R8o85-o6CnF_UEWZLWRK3a1gp57avR_uRyv8ZFUftw4vCnJT5dXnk1SStdjmWNEyeMHzPP-nY4RqGp8Oc4sAtrhVFGMB1ID5m0JJbULgDe-bO6NgzjHQGmA9rXe77PdblgsjzqZ8BxX9YKtd7URWSqMORUFBxQM8lzFR6IqP_yn6tieGQG6oa2bisqyP-1tGC_MSXFfi_26LAdYKLCSV3KRgs2DU9ilQFbaIBYY3YFgDrkByIccZufbQ5xiX9YdvH2wPGko5SlVasXA1H=s0-l75-ft-l75-ft))

![Web Image](https://gm1.ggpht.com/Dkr8w-HiFnT-9XJ2xtSUGOoj-ZO-I3XbHStrJTupAElS4U_ylbV4WeEPgiG8NCcPCSK2HW4FMNrMfA6Izsk9GWV4e2pF5JMVOs3_M2Ny2jiQyd9rEzmrJ_rroRBT_XIUWl13pRzoIJsWHoZztTQ5rF_d9Z54VuzSk2jTle5mpUXTmYDsiRap6xUaOqGAFv94G-mxjbi7ngtVblAYRDbOdQK7_xiHeR26byuuwr3GJq6l_mmjYm2KzBPR-kkE1G_MuJNc9tLaosQUTDycADkmOpy_58AthcyzibbsN5OxZuKarTxZYoLYKizRPc9Otg26RzabjT3PsSU8jRUp8yRrUPMS3bkWLt-I_OoaJASRfYtmgUmzxDUGbFCzJ-RZH_ZSip12LlLkerXl5jrijP1UjeQZUT2LmRG7cRchrBBRLm1qgVnydgPnwF5uD4PIg3S0xEiksOr2QIrTwRW8NTfjW4aQVrgeA1eLxtlsdN3Rub21XTCpvIgdOjG_ocABicTikY5gFTcNIUmAoEB_G8mVkv1fn5duWAKax-HML5U_xvoAxb7pTdujjlbrnVcke5AeFpIPtTYl0IcDvvc6NxT2lbUOrlqr-Ckkt-Qm4IB3MVitvfrqdzbs2C1ZnvXocN5TXDqUUs8MTOpw33A433E83bPxDIahbsQZX7tCJ-TlgtL-xR9ODAkAYY9pnqNVqH35BQDlkL5K25KQHyyGBDcCcHo0Lil6nNCeV5NGh0b3XGKiLcjyVanjHozXCsm3DhZe8utF518=s0-l75-ft-l75-ft)

Somethings that I have been learning in class that apply directly to my project is the content from the units. For every unit we have coding activites, which is similar to what I am doing now. I am doing and learning from coding activities that Firebase goes through in their videos. In regards to the **Engineering Design Process**, I am in Step 3 and Step 4, Brainstorming possible solutions and
Planning the most promising solution. I am continuing to brainstorm by doing research and understanding where exactly I need to begin from whether it's creating a bootstrap website and then using Firebase to host it or take a different approach. Some of the **skills** I have developed along the way are (1)How to read and (2)Embracing failure. I have come across the uncertainty of not knowing what steps to take next, but using Google and other sources has definitely helped me learn and find out what to do next.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
