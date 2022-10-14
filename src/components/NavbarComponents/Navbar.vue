<script setup lang="ts">
import SearchBar from './SearchBar.vue';
import ProfileDropDown from './ProfileDropdownComponent/ProfileDropDown.vue';
</script>

<template>
    <nav class="nav">
        <div class="navC1">
            <img src="/images/ytd.png" class="ytdlogo" />
            <div class="ttl">YouTube</div>
        </div>
        <div class="navC2">
            <SearchBar />
        </div>
        <div class="navC3">
            <ProfileDropDown />
        </div>
    </nav>
</template>

<style scoped>
.nav{
    width: 100%;
    height: 60px;
    padding: 0.5rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* background-color: aqua; */
}

.navC1{
    width: 200px;
    height: auto;
    display: flex;
    /* justify-content: center; */
    align-items: center;
}

.ytdlogo{
    width: 35px;
    height: 25px
}

.ttl{
    margin: 0 0.1rem;
    font-weight: bold;
    font-size: 1.1rem;
    color: var(--txt-color);
}
</style>