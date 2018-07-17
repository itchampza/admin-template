<template>
  <ul class="nav nav-mobile-menu">
    <li><a href="#" class="dropdown-toggle" data-toggle="dropdown">
      <i class="material-icons">dashboard</i>
      <p>Dashboard</p></a>
    </li>
    <li>
    </li>
    <li>
      <a href="#" data-toggle="dropdown" class="dropdown-toggle"><i class="material-icons">person</i>
      <p>Profile</p></a>
    </li>
  </ul>
</template>
<script>
export default {
  data () {
    return {
      search: null,
      selectedEmployee: null,
      employees: [
        'Jim Halpert',
        'Dwight Schrute',
        'Michael Scott',
        'Pam Beesly',
        'Angela Martin',
        'Kelly Kapoor',
        'Ryan Howard',
        'Kevin Malone'
      ]
    }
  }
}
</script>
