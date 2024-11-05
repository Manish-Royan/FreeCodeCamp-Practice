# This is Step 32

## Task
To improve accessibility of the image, add an `alt` attribute with the text: *`Five cats looking around a field`*.

**• Add**

```HTML
<html>
    <body>
        <main>
            <h1>CatPhotoApp</h1>
            <section>
            <h2>Cat Photos</h2>
            <!-- TODO: Add link to cat photos -->
            <p>See more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>
            <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
            </section>

            <section>
                <h2>Cat Lists</h2>
                <h3>Things cats love:</h3>
                <ul>
                    <li>cat nip</li>
                    <li>laser pointers</li>
                    <li>lasagna</li>
                </ul>
                <figure>
                    <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
                    <figcaption>Cats <em>love</em> lasagna.</figcaption>
                </figure>  
                
                <h3>Top 3 things cats hate:</h3>

                <ol>
                    <li>flea treatment</li>
                    <li>thunder</li>
                    <li>other cats</li>
                </ol>
                
                <figure> 
                <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt = "Five cats looking around a field"> <!-- Added here -->                
                </figure>
                
            </section>
        </main>
    </body>
</html>
```