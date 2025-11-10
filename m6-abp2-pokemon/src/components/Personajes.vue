<script>
export default {
  name: 'Personajes',
  data() {
    return {
      // Datos definidos dentro de un objeto, como exige el ejercicio
      personajesObj: {
        personajes: [
          {
            id: '1',
            nombre: 'pikachu',
            descripcion:
              'Cuando se enfada, este Pokémon descarga la energía que almacena en el interior de las bolsas de las mejillas.'
          },
          {
            id: '2',
            nombre: 'kakuna',
            descripcion:
              'Aunque es casi incapaz de moverse, en caso de sentirse amenazado puede envenenar a los enemigos con su aguijón.'
          },
          {
            id: '3',
            nombre: 'beedrill',
            descripcion:
              'Tiene tres aguijones venenosos, dos en las patas anteriores y uno en la parte baja del abdomen, con los que ataca a sus enemigos una y otra vez.'
          },
          {
            id: '4',
            nombre: 'metapod',
            descripcion:
              'Como en este estado solo puede endurecer su coraza, permanece inmóvil a la espera de evolucionar.'
          },
          {
            id: '5',
            nombre: 'rattata',
            descripcion:
              'Es propenso a hincar los incisivos en cualquier cosa que se le ponga por delante. Si se ve alguno, seguramente haya cuarenta cerca.'
          }
        ]
      }
    }
  }
}
</script>

<template>
  <div>
    <table class="table table-bordered">
      <thead>
        <tr>
          <th>ID</th>
          <th>Nombre</th>
          <th>Descripción</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="p in personajesObj.personajes" :key="p.id">
          <td>{{ p.id }}</td>
          <td class="text-capitalize">{{ p.nombre }}</td>
          <td class="text-start">{{ p.descripcion }}</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>


<style scoped>
table {
  border-radius: 12px;
  overflow: hidden;
}

thead th {
  background-color: #0d6efd !important;
  color: white;
}

tbody tr:hover {
  background-color: #e7f1ff !important;
  transition: background-color 0.2s ease;
}
</style>