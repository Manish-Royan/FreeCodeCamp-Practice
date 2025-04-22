# This is Step 34

## Task
1. **Semantic HTML**: The `<strong>` tag is a semantic element. It tells the browser (and screen readers) the meaning or importance of the enclosed text. In this case, it signifies that "hate" is a word of strong importance or urgency.

2. **Accessibility (a11y)**: When a screen reader encounters `<strong>` text, it can change its tone of voice to convey that emphasis to a user who is blind or has low vision. This provides crucial context that sighted users would get from the text being bolded.

3. **Pro Tip**: While `<strong>` typically makes text bold by default, you should never use it just for styling. If you just want bold text for visual design without any semantic meaning, you should use the CSS font-weight property instead. The `<strong>` tag is for meaning, not looks.

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
                <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt = "Five cats looking around a field"> 
                 <figcaption>Cats <strong>hate</strong> other cats.</figcaption> <!-- Added here -->                                
                </figure>
                
            </section>
        </main>
    </body>
</html>
```