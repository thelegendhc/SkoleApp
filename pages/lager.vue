<template>
    <v-simple-table>
    <template v-slot:default>
      <thead>
        <tr>
          <th class="text-left">
            Name
          </th>
          <th class="text-left">
            Amount
          </th>
        </tr>
      </thead>
      <tbody>
        <tr
          v-for="item in lager"
          :key="item.name"
        >
          <td>{{ item.name }}</td>
          <td>{{ item.amount }}</td>
        </tr>
      </tbody>
    </template>
  </v-simple-table>
</template>

<script>
export default {
    data () {
        return {
            lager: [
                {
                    name: "Søm",
                    amount: "1048"
                },
                {
                    name: "Skruer",
                    amount: "1100"
                }
                {
                name: "Bolte",
                amount: "1000"
                }
            ]
        }
    }
}
</script>
