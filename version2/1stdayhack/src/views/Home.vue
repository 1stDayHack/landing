<template>
    <span>
        <hero></hero>
        <AboutFirstday></AboutFirstday>
        <TentativeTracks></TentativeTracks>
        <Schedule></Schedule>
        <Sponsorship></Sponsorship>
        <Team></Team>
    </span>
</template>

<script>
import Hero from '@/components/Hero';
import AboutFirstday from '@/components/AboutFirstDayHack';
import TentativeTracks from '@/components/TentativeTracks';
import Schedule from '@/components/Schedule';
import Sponsorship from '@/components/Sponsorships';
import Team from '@/components/Team';

export default {
    name: 'Home',
    components: {
        Hero,
        AboutFirstday,
        TentativeTracks,
        Schedule,
        Sponsorship,
        Team
    }
}
</script>