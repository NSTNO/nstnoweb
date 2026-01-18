<template>
  <div class="min-h-screen bg-gradient-to-r from-blue-900 to-gray-900 flex items-center justify-center p-4 font-sans">
    <div class="bg-black/30 p-10 rounded-3xl flex flex-col items-center text-center max-w-sm border border-white/10 backdrop-blur-md">
      
      <span class="bg-blue-600/20 text-blue-400 text-xs font-black uppercase tracking-widest px-4 py-1.5 rounded-full border border-blue-500/20 mb-6">
        Founder
      </span>
      
      <NuxtImg 
        src="/normal.gif" 
        class="staff-circle mb-6 shadow-2xl" 
      />

      <h1 class="text-white text-2xl font-bold mb-3 tracking-tight">
        Normal Player
      </h1>
      
      <p class="text-gray-400 leading-relaxed">
        Normal Player is the founder of NSTNO, leading development of the MOD and website.
      </p>

    </div>
  </div>
</template>

<style scoped>
.staff-circle {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #1e293b;
}
</style>
