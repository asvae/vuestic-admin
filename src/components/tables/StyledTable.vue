<template>
  <table class="styled-table va-table">
    <thead>
    <tr>
      <td></td>
      <td>Name</td>
      <td>Email</td>
      <td>City</td>
      <td class="text-right">Score</td>
      <td align="middle"></td>
    </tr>
    </thead>
    <tbody>
    <tr :style="{backgroundColor: $themes.diluted.danger}">
      <td>
        <va-badge color="danger">danger</va-badge>
      </td>
      <td>Stanley Hummer</td>
      <td>mr_winner_2999@gmail.cb</td>
      <td>Manchester</td>
      <td align="right">57</td>
      <td align="middle">
        <va-icon
          icon="fa fa-exclamation-triangle"
          color="danger"
        />
      </td>
    </tr>
    <tr :style="{backgroundColor: $themes.diluted.success}">
      <td>
        <va-badge color="success">success</va-badge>
      </td>
      <td>Lendley Wintz</td>
      <td>9938198146@mailster.io</td>
      <td>Wien</td>
      <td align="right">113</td>
      <td align="middle">
        <va-icon :color="$themes.success" icon="fa fa-check"/>
      </td>
    </tr>
    <tr :style="{backgroundColor: $themes.diluted.warning}">
      <td>
        <va-badge color="warning">warning</va-badge>
      </td>
      <td>Barbara Noz</td>
      <td>barbaranoz@mailster.io</td>
      <td>Brussels</td>
      <td align="right">68</td>
      <td align="middle">
        <va-icon :color="$themes.warning" icon="fa fa-exclamation"/>
      </td>
    </tr>
    <tr :style="{backgroundColor: $themes.diluted.info}">
      <td>
        <va-badge color="info">info</va-badge>
      </td>
      <td>Nancy Bo</td>
      <td>nancy@boonweb.com</td>
      <td>Washington</td>
      <td align="right">280</td>
      <td align="middle">
        <va-icon :color="$themes.info" icon="fa fa-info"/>
      </td>
    </tr>
    </tbody>
  </table>
</template>

<script>
export default {
  name: 'styled-table',
}
</script>

<style lang="scss">
.styled-table {

}
</style>
