<script setup lang="ts">
import FlexBox from "./components/FlexBox.vue";
</script>

<template>
  <section>
    <code> display:flex; </code>
    <div class="contenedor1 contenedor">
      <FlexBox />
    </div>
  </section>

  <section>
    <code> flex-direction:row; </code>
    <div class="contenedor contenedor2">
      <FlexBox :cantidad="5" />
    </div>
  </section>
  <section>
    <code> flex-direction:row-reverse; </code>
    <div class="contenedor contenedor3">
      <FlexBox :cantidad="5" />
    </div>
  </section>
  <section>
    <code> flex-direction:column; </code>
    <div class="contenedor contenedor4">
      <FlexBox :cantidad="5" />
    </div>
  </section>
  <section>
    <code> flex-direction:column-reverse; </code>
    <div class="contenedor contenedor5">
      <FlexBox :cantidad="5" />
    </div>
  </section>

  <section>
    <code>flex-wrap:nowrap</code>
    <div class="contenedor contenedor6">
      <FlexBox :cantidad="25" />
    </div>
  </section>
  <section>
    <code>flex-wrap:wrap</code>
    <div class="contenedor contenedor7">
      <FlexBox :cantidad="25" />
    </div>
  </section>
  <section>
    <code>flex-wrap:wrap:reverse </code>
    <div class="contenedor contenedor8">
      <FlexBox :cantidad="25" />
    </div>
  </section>
  <section>
    <code>flex-flow:colunm-wrap </code>
    <div class="contenedor contenedor9">
      <FlexBox :cantidad="20" />
    </div>
  </section>
  <section>
    <code>flex-flow:colunm reverse-wrap </code>
    <div class="contenedor contenedor10">
      <FlexBox :cantidad="20" />
    </div>
  </section>
  <section>
    <code>flex-flow:wrap reverse-column </code>
    <div class="contenedor contenedor11">
      <FlexBox :cantidad="20" />
    </div>
  </section>
  <section>
    <code>flex-flow:wrap reverse-column reverse </code>
    <div class="contenedor contenedor12">
      <FlexBox :cantidad="20" />
    </div>
  </section>
  <section>
    <code>justify-content:flex-start </code>
    <div class="contenedor contenedor13">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>justify-content:center </code>
    <div class="contenedor contenedor14">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>justify-content:flex-end </code>
    <div class="contenedor contenedor15">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>justify-content:space-between </code>
    <div class="contenedor contenedor16">
      <FlexBox :cantidad="8" />
    </div>
  </section>
  <section>
    <code>justify-content:space-around </code>
    <div class="contenedor contenedor17">
      <FlexBox :cantidad="8" />
    </div>
  </section>
  <section>
    <code>justify-content:space-evenly </code>
    <div class="contenedor contenedor18">
      <FlexBox :cantidad="8" />
    </div>
  </section>
  <section>
    <code>align-items:stretch </code>
    <div class="contenedor contenedor19">
      <FlexBox :cantidad="20" />
    </div>
  </section>
  <section>
    <code>align-items: flex-start </code>
    <div class="contenedor contenedor20">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>align-items: center </code>
    <div class="contenedor contenedor21">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>align-items: flex-end </code>
    <div class="contenedor contenedor22">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>align-items: baseline </code>
    <div class="contenedor contenedor23">
      <FlexBox :cantidad="10" />
    </div>
  </section>

  <section>
    <code>align-items: center; justify-content:space-evenly </code>
    <div class="contenedor contenedor24">
      <FlexBox :cantidad="6" />
    </div>
  </section>
  <section>
    <code>align-self: </code>
    <div class="contenedor contenedor25">
      <FlexBox :cantidad="5" />
    </div>
  </section>
  <section>
    <code>order </code>
    <div class="contenedor contenedor26">
      <FlexBox :cantidad="5" />
    </div>
  </section>
  <section>
    <code>flex-grow </code>
    <div class="contenedor contenedor27">
      <FlexBox :cantidad="5" />
    </div>
  </section>
  <section>
    <code>flex-shrink </code>
    <div class="contenedor contenedor28">
      <FlexBox :cantidad="30" />
    </div>
  </section>
  <section>
    <code>flex-bassis </code>
    <div class="contenedor contenedor29">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>flex </code>
    <div class="contenedor contenedor30">
      <FlexBox :cantidad="10" />
    </div>
  </section>
  <section>
    <code>flexbox </code>
    <div class="contenedor contenedor31">
      <FlexBox :cantidad="3" />
    </div>
  </section>
  <section>
    <code>flexbox </code>
    <div class="contenedor contenedor32">
      <FlexBox :cantidad="8" />
    </div>
  </section>
  <section>
    <code>flexbox </code>
    <div class="contenedor contenedor33">
      <div class="hijo1"></div>
      <div class="hijo2"><FlexBox :cantidad="3" /></div>
      <div class="hijo3"><FlexBox :cantidad="4" /></div>
    </div>
  </section>
</template>

<style lang="scss">
.contenedor {
  margin-bottom: 20px;
  background-color: aliceblue;
  min-height: 200px;
}
.contenedor1 {
  display: flex;
}
.contenedor2 {
  display: flex;
  flex-direction: row;
}
.contenedor3 {
  display: flex;
  flex-direction: row-reverse;
}
.contenedor4 {
  display: flex;
  flex-direction: column;
}
.contenedor5 {
  display: flex;
  flex-direction: column-reverse;
}
.contenedor6 {
  display: flex;
  flex-wrap: nowrap;
}
.contenedor7 {
  display: flex;
  flex-wrap: wrap;
}
.contenedor8 {
  display: flex;
  flex-wrap: wrap-reverse;
}
.contenedor9 {
  display: flex;
  flex-flow: column wrap;
  height: 500px;
}
.contenedor10 {
  display: flex;
  flex-flow: column-reverse wrap;
  height: 450px;
}
.contenedor11 {
  display: flex;
  flex-flow: wrap-reverse column;
  height: 450px;
}
.contenedor12 {
  display: flex;
  flex-flow: wrap-reverse column-reverse;
  height: 450px;
}
.contenedor13 {
  display: flex;
  justify-content: flex-start;
}
.contenedor14 {
  display: flex;
  justify-content: center;
}
.contenedor15 {
  display: flex;
  justify-content: flex-end;
}
.contenedor16 {
  display: flex;
  justify-content: space-between;
}
.contenedor17 {
  display: flex;
  justify-content: space-around;
}
.contenedor18 {
  display: flex;
  justify-content: space-evenly;
}
.contenedor19 {
  display: flex;
  align-items: str;
  .box {
    height: auto;
  }
}
.contenedor20 {
  display: flex;
  align-items: flex-start;
}
.contenedor21 {
  display: flex;
  align-items: center;
}
.contenedor22 {
  display: flex;
  align-items: flex-end;
}
.contenedor23 {
  display: flex;
  align-items: baseline;
}

.contenedor24 {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  height: 300px;
}
.contenedor25 {
  display: flex;

  :nth-child(1) {
    align-self: flex-end;
  }
  :nth-child(2) {
    align-self: stretch;
    height: auto;
  }
  :nth-child(3) {
    align-self: flex-start;
  }
  :nth-child(4) {
    align-self: center;
  }
  :nth-child(5) {
    align-self: baseline;
  }
}
.contenedor26 {
  display: flex;
  :nth-child(5) {
    order: 1;
  }
  :nth-child(4) {
    order: 2;
  }
  :nth-child(3) {
    order: 3;
  }
  :nth-child(1) {
    order: 5;
  }
  :nth-child(2) {
    order: 4;
  }
}
.contenedor27 {
  display: flex;
  :nth-child(2) {
    flex-grow: 0.1;
  }
  :nth-child(4) {
    flex-grow: 0.1;
  }
}
.contenedor28 {
  display: flex;
  :nth-child(4) {
    flex-shrink: 1.5;
  }
}
.contenedor29 {
  display: flex;
  :nth-child(4) {
    flex-basis: 50%;
  }
}
.contenedor30 {
  display: flex;
  :nth-child(4) {
    flex: 0.1 0.5 200px;
  }
}
.contenedor31 {
  display: flex;
  flex-wrap: wrap;
  justify-content: end;
  .box {
    height: 300px;
  }

  :nth-child(1) {
    flex-basis: 50%;
    display: flex;
    justify-content: center;
  }
  :nth-child(2) {
    flex-basis: 50%;
  }
  :nth-child(3) {
    flex-basis: 100%;
  }
}
.contenedor32 {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  .box {
    height: 200px;
    margin-bottom: 30px;
    margin-top: 30px;
    border-radius: 30px;
  }
  :nth-child(1) {
    flex-basis: 20%;
    display: flex;
    justify-content: center;
  }
  :nth-child(2) {
    flex-basis: 20%;
  }
  :nth-child(3) {
    flex-basis: 20%;
  }
  :nth-child(4) {
    flex-basis: 20%;
  }
  :nth-child(5) {
    flex-basis: 45%;
  }
  :nth-child(6) {
    flex-basis: 45%;
  }
  :nth-child(7) {
    flex-basis: 95%;
  }
  :nth-child(8) {
    flex-basis: 95%;
  }
}
.contenedor33 {
  display: flex;
  height: 900px;
  justify-content: center;
  .box {
    height: 300px;
    margin-top: 10px;
    margin-bottom: 2%;
    margin-left: 10px;
  }
  .hijo1 {
    display: flex;
    width: 20%;
    background-color: aquamarine;
    margin-top: 10px;
  }
  .hijo2 {
    display: flex;
    width: 20%;

    flex-wrap: wrap;
    :nth-child(1) {
      flex-basis: 100%;
      height: 19%;
    }
    :nth-child(2) {
      flex-basis: 100%;
      height: 38%;
    }
    :nth-child(3) {
      flex-basis: 100%;
      height: 38%;
    }
  }

  .hijo3 {
    display: flex;
    width: 40%;

    flex-wrap: wrap;

    :nth-child(1) {
      flex-basis: 100%;
      height: 38%;
    }
    :nth-child(2) {
      flex-basis: 60%;
      height: 37%;
    }
    :nth-child(3) {
      flex-basis: 37%;
      height: 37%;
    }
    :nth-child(4) {
      flex-basis: 100%;
      height: 18.5%;
    }
  }
}
</style>
