<!DOCTYPE html>
<html>
   <head lang="en">
      <meta charset="utf-8">
      <title>CatPhotoApp</title>
   </head>
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
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>  
        </figure>
      </section>
      <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
           <fieldset>
              <legend>Is your cat indoor or outdoor</legend>
             <label><input type="radio" name="indoor-outdoor" id="indoor" value="indoor"checked>Indoor</label>
              <label><input type="radio" name="indoor-outdoor" id="outdoor" value="outdoor">Outdoor</label>
             <legend>what's your cat's personality</legend>
              <input type="checkbox" id="loving" name="personality" value="loving"checked><label for="loving">Loving</label>
              <input type="checkbox" id="lazy" name="personality" value="lazy"><label for="lazy">Lazy</label>
              <input type="checkbox" id="energetic" name="personality" value="energetic"><label for="energetic">Energetic</label>
           </fieldset>
           <button type="submit">Submit</button>
        </form>
      </section>
    </main>
     <footer>
<p>No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a></p>
     </footer>
  </body>
