<template>
  <div id="app" class="small-container">
    <h1>Avengers</h1>

    <employee-form />
    <employee-table :employees="employees" />
    <employee-table @add:employee="add-employee" />
  </div>
</template>

<script>
import EmployeeTable from './components/EmployeeTable.vue'
import EmployeeForm from './components/EmployeeForm.vue'

export default {
  name: 'app',
  components: {
    EmployeeTable,
    EmployeeForm,
  },
  data() {
    return {
      employees: [
        {
          id: 1,
          name: 'Thor of Asgard',
          email: 'thor@avengers.com',
        },
        {
          id: 2,
          name: 'Captain America',
          email: 'cap@avengers.com',
        },
        {
          id: 3,
          name: 'Tony Stark',
          email: 'ironman@avengers.com',
        },
        {
          id: 4,
          name: 'Natasha Romanoff',
          email: 'blackwidow@avengers.com',
        },
        {
          id: 5,
          name: 'Bruce Banner',
          email: 'hulk@avengers.com',
        },
        {
          id: 6,
          name: 'Carole Danvers',
          email: 'captainmarvel@avengers.com',
        },
        {
          id: 7,
          name: 'TChalla',
          email: 'blackpanther@avengers.com',
        },
        {
          id: 8,
          name: 'Clint Barton',
          email: 'hawkeye@avengers.com',
        },
      ],
    }
  },
}

</script>