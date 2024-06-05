<template>
     <div>
        <div class="repo-card">
            <h2 class="skeleton hdn"></h2>
            <div class="repo-mini-details">
                <div class="skeleton icn"></div>
                <div class="skeleton icn"></div>
                <div class="skeleton icn"></div>
                <div class="skeleton icn"></div>
            </div>
            <div class="skeleton pgph"></div>
            <div class="skeleton pgph"></div>
            <div class="skeleton pgph"></div>
        </div>
    </div>
</template>

<style>
.skeleton {
    width: 100%;
    height: 1rem;
    border-radius: 0.7rem;
    animation: pulse-bg 1.5s infinite;
    margin: 1rem 0;
}

.hdn {
    width: 100%;
    height: 1.5rem;
}

.pgph {
    width: 40%;
    height: 1.2rem;
}

.icn {
    height: 1.2rem;
}

@keyframes pulse-bg {
    0% {
        background-color: #80808024;
    }
    
    50% {
        background-color: #808080;  
    } 

    100% {
        background-color: #80808024;
    }
}
</style>