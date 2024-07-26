# This is Step 24

We learned about the `figurecaption` element is used to **add a caption** to describe the image contained within the `figure` element.

## Example
```HTML
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
```

## Task

After the image nested in the figure element, add a figcaption element with text set to:
*`Cats love lasagna.`*

**• Add**

```HTML
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
          <figcaption>Cats love lasagna.</figcaption> <!-- Add here -->
          </figure>
        </section>
    </main>
```
