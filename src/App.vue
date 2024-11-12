<template>
  <div class="print-container">
    <table>
      <thead class="header">
        <tr class="header-content">
          <th class="header-left">
            <p style="font-size: 12px; font-weight: 700;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
          </th>
          <th>
            <img style="width: 50px;" src="./assets/vue.svg" alt="vueimg">
          </th>
          <th class="header-right">
            <p style="font-size: 12px; font-weight: 700;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>

          </th>
        </tr>
      </thead>
      <tbody>
        <tr style="display: grid; grid-template-columns: 1fr 1fr 1fr;">
          <td style="text-align: left;">
            <span style="background-color: gray; font-size: 13px; font-weight: 600;">Lorem, ipsum dolor.</span>
            <div style="font-size: 12px; font-weight: 400;">Lorem</div>
            <div style="font-size: 12px;">Lorem, ipsum dolor.</div>
          </td>
          <td style="text-align: left;">
            <span style="font-size: 12px; font-weight: 800;">Submitted</span>
            <span style="font-size: 12px;">10/4/2024</span>
          </td>
          <td style="text-align: left;">
            <span style="font-size: 12px; font-weight: 800;">Submitted</span>
            <span style="font-size: 12px;">10/4/2024</span>
          </td>
        </tr>
        <tr>
          <td style="text-align: left;">
            <span style="background-color: gray; font-size: 13px; font-weight: 600;">Lorem, ipsum dolor.</span>
            <p style="font-size: 12px;">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora quis
              architecto quaerat eum accusamus! Officiis harum quisquam provident aut est ducimus inventore, cumque odio
              itaque libero deserunt tempore totam doloremque labore dicta eos ex perspiciatis pariatur nobis laboriosam
              aspernatur dolores. Deserunt unde commodi consectetur nesciunt?</p>
            <hr color="#c7c3c3" width="99%">

          </td>
        </tr>
        <tr>
          <td style="text-align: left;">
            <span style="background-color: gray; font-size: 13px; font-weight: 600;">Lorem, ipsum dolor.</span>
            <p style="font-size: 13px; font-weight: 600;margin-bottom: 10px;">Lorem, ipsum</p>
            <p style="font-size: 12px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur dolorum
              aspernatur totam necessitatibus accusantium doloremque voluptate voluptatem ullam amet exercitationem et
              incidunt autem magni, provident porro omnis eligendi? Iste eos explicabo molestias, blanditiis culpa hic
              beatae inventore amet magni ducimus ullam repellat facere excepturi impedit ea officia architecto nulla.
              Dolores iure error qui quam, aut voluptatibus totam officiis voluptate repudiandae laudantium esse
              cupiditate perferendis tempora at facere distinctio quidem inventore vitae sunt consectetur repellat
              aspernatur temporibus animi eveniet? Minus nisi optio totam earum! Ex dolore nemo consectetur eum, quidem
              esse assumenda aliquam provident earum, at possimus ut eius dolor? Quia voluptas excepturi eligendi
              quibusdam nihil non illo sapiente dicta inventore consectetur reiciendis odit doloremque porro asperiores
              fugiat libero maiores, eaque officiis aperiam vero ex consequatur veniam! Aliquid magnam pariatur nam
              obcaecati corrupti nobis. Laboriosam quod delectus nemo maxime reiciendis, minima facere ullam excepturi
              aliquid eligendi! Nemo atque obcaecati ea reiciendis repudiandae nihil aspernatur alias odio accusamus,
              ipsa esse minus quidem veritatis non illo, voluptatum soluta labore. Architecto impedit natus corporis
              quis fugit ullam. Officiis suscipit facilis animi aliquid excepturi voluptatum incidunt, magnam fuga?
              Omnis, explicabo maxime. Atque vero ratione molestiae id possimus, ab hic saepe illo, nisi non velit
              aliquam!</p>

            <p style="font-size: 13px; font-weight: 600;margin: 10px 0px;">Lorem, ipsum</p>
            <p style="font-size: 12px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia ex saepe
              temporibus, est nisi tempora excepturi quasi odit unde, nobis reprehenderit numquam, sapiente itaque
              exercitationem repellat placeat doloremque tenetur neque earum hic officiis quae sequi ea nemo. Beatae
              odio ducimus tenetur aliquam a quasi architecto voluptatibus, adipisci recusandae officiis non!</p>

            <p style="font-size: 13px; font-weight: 600;margin: 10px 0px;">Lorem, ipsum</p>
            <p style="font-size: 12px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia ex saepe
              temporibus, est nisi tempora excepturi quasi odit unde, nobis reprehenderit numquam, sapiente itaque
              exercitationem repellat placeat doloremque tenetur neque earum hic officiis quae sequi ea nemo. Beatae
              odio ducimus tenetur aliquam a quasi architecto voluptatibus, adipisci recusandae officiis non!</p>
          </td>
        </tr>
        <tr>
          <td colspan="4">
            <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 10px; padding: 10px;">
              <div v-for="(item, index) in imgLists" :key="index"
                style="flex: 1 1 45%; height: 150; display: flex; justify-content: center; align-items: center; color: white;page-break-inside:avoid; ">
                <img :src="item" alt="" style="max-width: 90%;max-height: 130px; ">
              </div>
            </div>
          </td>
        </tr>
      </tbody>
      <tfoot class="footer">
        <tr class="footer-content">
          <td class="footer-left">
            <p style="font-size: 12px; font-weight: 700;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
            <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
          </td>
          <td class="footer-center">
            <div style="text-align: left; line-gap-override: 0.5px; text-align: center;">
              <p style="font-size: 12px; font-weight: 700;">Lorem, ipsum dolor.</p>
              <p style="font-size: 9px;margin-top: 5px;">Lorem, ipsum dolor.</p>
              <p style="font-size: 9px;">Lorem, ipsum dolor.</p>
            </div>
          </td>
          <td class="footer-right">
            <img style="width: 50px;" src="./assets/vue.svg" alt="vueimg">
          </td>
        </tr>
      </tfoot>
    </table>
  </div>
</template>

<script setup>

import { imgLists } from './constant/index'
function printIt() {
  window.print();
}

</script>

<style scoped>
table {
  width: 100%;
  text-align: center;
}

.header {
  width: 100%;
}

.header-content {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  align-items: center;
  padding: 8px 15px;
}

.header-left {
  text-align: left;
  line-gap-override: 0.5px;
}

.header-right {
  text-align: right;
}

.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: white;
}

.footer-content {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  align-items: center;
  padding: 8px 15px;
}

.footer-left {
  text-align: left;
  line-gap-override: 0.5px;
}

.footer-center {
  text-align: center;
  line-gap-override: 0.5px;
}

.footer-right {
  text-align: right;
  margin-right: 15px;
}

p {
  margin: 0;
}

@media print {
  .print-container {
    display: block;
    min-height: 100vh;
  }

  .header {
    width: 100%;
  }
  .footer {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    text-align: center;
    font-size: 12px;
    color: black;
  }
}
</style>