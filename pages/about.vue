<template>
  <section class="container">
    <h1>About</h1>
    <router-link to="/">TOP</router-link>
    <p>Nice to meet you.</p>
    <table>
      <tbody>
      <tr>
        <th>Name</th>
        <td>{{ name }}</td>
      </tr>
      <tr>
        <th>Age</th>
        <td>{{ age }}</td>
      </tr>
      <tr>
        <th>Address</th>
        <td>{{ address }}</td>
      </tr>
      <tr>
        <th>Job</th>
        <td>{{ job }}</td>
      </tr>
      </tbody>
    </table>
  </section>
</template>

<script>
export default {
  //Promiseを返す
  asyncData ({params}) {
    return {job: 'Engineer'}
  },
  data: function () {
    return {
      name: 'Taro',
      age: 30,
      address: 'Japan',
      job: 'Sales'
    }
  },
  head () {
    return {
      title: 'About'
    }
  }
}
</script>

<style>
table {
  margin-top : 20px;
}
th {
  background: #fc0;
  padding:5px;
  color: black;
}
td {
  padding: 5px;
}
</style>

