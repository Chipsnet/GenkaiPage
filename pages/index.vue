<template>
    <div>
        <section class="hero is-medium is-primary is-bold">
            <div class="hero-body">
                <div class="container">
                    <h1 class="title">
                        {{ $t("top_message") }}
                    </h1>
                    <h2 class="subtitle">
                        {{ $t("top_subtitle") }}
                    </h2>
                </div>
            </div>
        </section>
        <section class="section">
            <div class="container py-6 has-text-centered">
                <h1 class="title mt-6">{{ $t("can_title") }}</h1>
                <div class="columns my-6 is-desktop">
                    <div class="column">
                        <h2 class="title is-2">{{ $t("can_title1") }}</h2>
                        <p class="subtitle is-5 mt-3">
                            {{ $t("can_content1") }}
                        </p>
                    </div>
                    <div class="column">
                        <h2 class="title is-2">{{ $t("can_title2") }}</h2>
                        <p class="subtitle is-5 mt-3">
                            {{ $t("can_content2") }}
                        </p>
                    </div>
                    <div class="column">
                        <h2 class="title is-2">{{ $t("can_title3") }}</h2>
                        <p class="subtitle is-5 mt-3">
                            {{ $t("can_content3") }}
                        </p>
                    </div>
                </div>
                <b-button
                    type="is-primary"
                    class="font"
                    tag="router-link"
                    to="#"
                    >{{ $t('now_join') }}</b-button
                >
            </div>
        </section>
        <section class="section why">
            <div class="container pt-6 mb-5">
                <h1 class="title is-2 has-text-white">{{ $t("why") }}</h1>
            </div>
            <div class="container pb-6">
                <h1 class="title mb-5 has-text-white">
                    {{ $t("sec1_title") }}
                </h1>
                <h2 class="subtitle has-text-white">
                    {{ $t("sec1_content") }}
                </h2>
            </div>
            <div class="container pb-6 pt-3">
                <h1 class="title mb-5 has-text-white">
                    {{ $t("sec2_title") }}
                </h1>
                <h2 class="subtitle has-text-white">
                    {{ $t("sec2_content") }}
                </h2>
            </div>
            <div class="container pb-6 pt-3">
                <h1 class="title mb-5 has-text-white">
                    {{ $t("sec3_title") }}
                </h1>
                <h2 class="subtitle has-text-white">
                    {{ $t("sec3_content") }}
                </h2>
            </div>
        </section>
    </div>
</template>

<style>
.section {
    white-space: pre-line;
}

.why {
    background: rgb(3, 0, 54);
    background: linear-gradient(
        110deg,
        rgba(3, 0, 54, 1) 0%,
        rgba(9, 9, 121, 1) 58%,
        rgba(0, 212, 255, 1) 100%
    );
}

.font {
    font-family: a-otf-midashi-go-mb31-pr6n, sans-serif;
    font-weight: 600;
    font-style: normal;
}
</style>
