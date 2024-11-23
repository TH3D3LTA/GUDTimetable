<script setup>
    import LessonCard from "./components/LessonCard.vue";
</script>

<template>
    <section class="flex flex-col bg-gradient-to-b from-black to-white margin-0 h-screen overflow-hidden items-center">
        <div class="flex flex-col py-16 items-center">
            <p class="prata text-white text-[32px] w-fit">21 ноября, чт</p>
            <p class="inter text-white text-[16px] font-regular w-fit">нечётная неделя</p>
        </div>
        <div class="py-2 bg-[--container-dark] flex flex-col gap-2 text-white h-full p-2 rounded-t-[24px] w-full overflow-y-auto">
            <LessonCard />
            <LessonCard />
            <LessonCard />
            <LessonCard />
        </div>
    </section>
</template>
