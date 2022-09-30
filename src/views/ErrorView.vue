<script setup>
  import WarningIcon from "../components/WarningIcon.vue";
  </script>
  
  <template>
    <main class="w-full h-screen bg-gray-50 pt-36 flex justify-center items-start">
      <div class="w-full md:container py-8 px-8 flex flex-col justify-center items-stretch space-y-4">
        <div class="rounded-3xl bg-white p-6 flex justify-center items-start space-x-4">
          <WarningIcon class="min-w-[30px] min-h-[30px] w-[30px] h-[30px] mt-1 fill-orange-400"></WarningIcon>
          <h1 class="text-3xl font-medium tracking-tight text-gray-600">There was an error when saving your payout verification settings.</h1>
        </div>
        <div class="rounded-3xl bg-white p-6 flex justify-center items-start space-x-4">
          <h2 class="text-xl font-medium tracking-tight text-gray-600">Please go back and try again</h2>
        </div>
      </div>
    </main>
  </template>
  