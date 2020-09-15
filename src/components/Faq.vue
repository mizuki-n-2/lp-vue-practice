<template>
  <div class="faq wrap">
    <table>
      <tr>
        <th>FAQ</th>
        <td class="text">良くある質問</td>
      </tr>
    </table>
  </div>
</template>

<style scoped>
.faq {
  background: #000;
  color: #f2f2f2;
  height: 80px;
  line-height: 80px;
  margin-bottom: 100px;
  position: relative;
}

.faq td {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
}

.faq th {
  font-size: 24px;
  font-family: Arial, Helvetica, sans-serif;
}

.faq table {
  width: 95%;
  margin: 0 auto;
  text-align: left;
}

@media screen and (max-width: 768px) {
  .faq {
    width: 95%;
    height: 120px;
    line-height: 120px;
    margin-bottom: 50px;
  }

  .faq table {
    width: 80%;
  }
}
</style>