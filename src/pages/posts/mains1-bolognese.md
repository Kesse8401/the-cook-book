---
title: BOLOGNESE
layout: ../../layouts/BlogLayout.astro
style: import '../../styles/global.css';
---

<!-- <header class="header"> -->

  <main>

# RAG&#218; ALLA BOLOGNESE

  <img class="foodImage" src="/images/bolognese.jpeg" alt="starters" />

  <div class="recipe">
    <div class="ingredients">
      <h1 class="IngHead">Ingredients</h1>
      <ul class="listOfIng">
        <li>800gr Mince Beef</li>
        <li>800gr of San Marzano tomatoes (canned)</li>
        <li>200gr Pancetta</li>
        <li>2 tbsp Tomato puree</li>
        <li>1 glass of red wine (optional but recommended)</li>
        <li>3 or 4 cloves of garlic</li>
        <li>Mirepoix ok 300gr</li>
        <li>2 bayleafs</li>
        <li>Salt and Pepper</li>
        <li>Pecorino or Parmigiano rind</li>
        <li>Bunch of parsley</li>
        <li>Small bunch of basil</li>
        <li>Glass of milk or 12% cream</li>
      </ul>
    </div>
    <div class="instructions">
      <h1 class="IngHead">Instructions</h1>
      <p class="parInstruct">
        1. Fry pancetta and set aside. Fry mirepoix using residual fat. Once
        soften put it aside. Brown the meat in batches. Fry tomato puree for a
        30 sec. Add everything back to the pan/pot. Deglaze with wine. Add
        leafs. When wine evaporates add stock, tomatoes and cheese rinds.
      </p>
      <p class="parInstruct">
        2. Cook on low for few hours. Stir ocassionally.
      </p>
      <p class="parInstruct">
        3. Add glass of full milk or 12% cream, mix and boil gently for few
        minutes. Kill the heat and add chopped basil and parsley.
      </p>
      <p class="parInstruct">
        4. Serve with pasta, use for lasagne or freeze in batches.
      </p>
      <p class="parInstruct"></p>
      <p class="parInstruct"></p>
    </div>
  </div>
</main>

  <style>

    .ingredients {
      width: 60%;
      text-align: left;
      margin: 25px;
      margin-bottom: 40px;
    }

    .header {
      font-weight: 700;
      font-size: 30px;
    }

    .foodImage {
      height: 350px;
      width: 350px;
      border-radius: 0.5rem;
      opacity: 0.8;
    }

    .IngHead {
      font-size: 20px;
      margin: 20px;
    }

    .listOfIng {
      list-style: none;
      margin-left: 40px;
      font-size: 18px;
      line-height: 2.1;
    }

    ul {
      padding: 0;
    }

    .instructions {
        text-align: left;
        margin: 25px;
    }

    .parInstruct {
      margin-left: 40px;
      font-size: 18px;
      line-height: 2.1;
      margin-bottom: 30px;
    }

@media screen and (max-width: 400px) {
      .recipe {
        display: grid;
        grid-template-columns: 1fr;
        grid-template-rows: repeat(2, 1fr);
  }
}

@media screen and (min-width: 400px) and (max-width: 900px) {
  .recipe {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 0px;
    grid-row-gap: 0px;
  }
}

@media screen and (min-width: 901px) {
  .recipe {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 0px;
    grid-row-gap: 0px;
  }
}

  </style>
</header>
