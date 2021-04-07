<template>
  <div>
    <h2 class="title">Frequently Asked Questions</h2>
    <div class="accordion-item">
      <h2 class="header">This is a testing question</h2>
      <p class="answer">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut cumque illo sed sequi ab magnam dicta, alias maiores
        repellendus recusandae id enim porro, perferendis molestias in animi quas qui eaque commodi, quod iste pariatur
        harum consequatur quisquam. Cupiditate vel nihil quisquam adipisci sequi possimus quasi doloremque facere magnam
        quod quia qui quo modi dicta totam nulla veritatis et, placeat culpa obcaecati! Illo beatae laborum ipsum, neque
        minima, nihil quod dolor veritatis quam provident quis! Consequuntur doloremque cumque quis totam nostrum
        quaerat provident? Corporis eum temporibus minima atque cum delectus molestiae accusamus quaerat! Quae
        accusantium unde veniam, perspiciatis debitis ut voluptatem.
      </p>
    </div>
    <div class="accordion-item">
      <h2 class="header">This is a testing question</h2>
      <p class="answer">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut cumque illo sed sequi ab magnam dicta, alias maiores
        repellendus recusandae id enim porro, perferendis molestias in animi quas qui eaque commodi, quod iste pariatur
        harum consequatur quisquam. Cupiditate vel nihil quisquam adipisci sequi possimus quasi doloremque facere magnam
        quod quia qui quo modi dicta totam nulla veritatis et, placeat culpa obcaecati! Illo beatae laborum ipsum, neque
        minima, nihil quod dolor veritatis quam provident quis! Consequuntur doloremque cumque quis totam nostrum
        quaerat provident? Corporis eum temporibus minima atque cum delectus molestiae accusamus quaerat! Quae
        accusantium unde veniam, perspiciatis debitis ut voluptatem.
      </p>
    </div>
    <div class="accordion-item">
      <h2 class="header">This is a testing question</h2>
      <p class="answer">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut cumque illo sed sequi ab magnam dicta, alias maiores
        repellendus recusandae id enim porro, perferendis molestias in animi quas qui eaque commodi, quod iste pariatur
        harum consequatur quisquam. Cupiditate vel nihil quisquam adipisci sequi possimus quasi doloremque facere magnam
        quod quia qui quo modi dicta totam nulla veritatis et, placeat culpa obcaecati! Illo beatae laborum ipsum, neque
        minima, nihil quod dolor veritatis quam provident quis! Consequuntur doloremque cumque quis totam nostrum
        quaerat provident? Corporis eum temporibus minima atque cum delectus molestiae accusamus quaerat! Quae
        accusantium unde veniam, perspiciatis debitis ut voluptatem.
      </p>
    </div>
    <div class="accordion-item">
      <h2 class="header">This is a testing question</h2>
      <p class="answer">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut cumque illo sed sequi ab magnam dicta, alias maiores
        repellendus recusandae id enim porro, perferendis molestias in animi quas qui eaque commodi, quod iste pariatur
        harum consequatur quisquam. Cupiditate vel nihil quisquam adipisci sequi possimus quasi doloremque facere magnam
        quod quia qui quo modi dicta totam nulla veritatis et, placeat culpa obcaecati! Illo beatae laborum ipsum, neque
        minima, nihil quod dolor veritatis quam provident quis! Consequuntur doloremque cumque quis totam nostrum
        quaerat provident? Corporis eum temporibus minima atque cum delectus molestiae accusamus quaerat! Quae
        accusantium unde veniam, perspiciatis debitis ut voluptatem.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  data() {},
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Raleway", sans-serif;
}

body {
  background-color: #082d52;
}

.title {
  color: #fff;
  margin-bottom: 32px;
}

.accordion {
  padding: 50px;
  max-width: 1200px;
  margin: 0 auto;
}

.accordion-item {
  border-radius: 10px;
  padding: 20px;
  margin-bottom: 20px;
  background-color: #fff;
}

.header {
  align-items: center;
  display: flex;
  cursor: pointer;
}

.header::after {
  content: "+";
  font-size: 40px;
  margin-left: auto;
}

.header-active::after {
  content: "-";
}

.answer {
  transition: 1000ms ease max-height;
  max-height: 0;
  overflow: hidden;
}
</style>
