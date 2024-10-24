# The Client - Website

Ontwerp en maak een website voor een opdrachtgever en bespreek het resultaat tijdens de Sprint Review.

## Inhoudsopgave Readme

  * [Intro](#intro)
  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Licentie](#licentie)

## Intro
De opdrachtgever had de opdracht gegeven om aan de hand van het bestaande Figma bestand een website te creëeren. Deze website zou een webapp moeten worden met als doelgroep ouders met jonge kinderen. Dit is het resultaat van de opdracht.<br>
https://kitkatisvibing.github.io/the-client-website/

## Beschrijving

Op een mobiel ziet de homepage van de website er zo uit. De kleuren zijn iets aangepast ivm toegankelijkheid. De knop 'lets do it' brengt je direct naar de lessons page, en de menu knop brengt je naar het menu.
<br><br>
![image](https://github.com/user-attachments/assets/8fea8992-525c-435b-82ee-f0f5dba2deaf)
<br>
De homepage is voor een deel ook al responsive. De positie van de muis en spraakwolk veranderen om beter op het scherm te passen.
<br>
![image](https://github.com/user-attachments/assets/cb3d9ce0-774f-4be1-a2fc-8c154b69b8b3)


## Kenmerken
In de html van dit project wordt veel gebruik gemaakt van classes en achor tags. Hier is een voorbeeld. 
```
 <article class="speechbubble">	
			<p>Good morning, shall we start with a story?</p>
			<a href="pages/lessons.html" class="storiesbutton">Let's do it!</a>
		</article>
```

om de homepage responsive te makken is er gebruik gemaakt van een media query in css. 
```
@media screen and (min-width:600px) {
	.mouse{
		margin-top:-10%;
		scale:60%;
		align-items: flex-start;
	}

	.speechbubble{
		display:inline-flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		background-color: whitesmoke;
		border-radius: 20px;
		padding: 15px 5px;
	}
}
```
## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
