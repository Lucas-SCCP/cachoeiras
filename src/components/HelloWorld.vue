<template>
  <div class="min-h-screen bg-gray-100">
    <header class="bg-white border-b border-gray-200">
      <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-bold leading-tight text-gray-900">
          Meu Projeto
        </h1>
      </div>
    </header>
    <main>
      <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
        <!-- Conteúdo principal do aplicativo -->
        <slot></slot>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'AppLayout'
}
</script>
