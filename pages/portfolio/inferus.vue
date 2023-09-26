<template>
  <PortfolioPage>
    <Details :list="project" />
  </PortfolioPage>
</template>

<script>
export default {
  name: "MovieBox page",
  layout: "portfolio",
  data() {
    return {
      project: {
        outcome: [
          "This product is currently in beta testing and the MVP would be released shortly after, this tool is aimed at providing user's with unlimmited movie stream.",
        ],
        description: [
          "Developed a revolutionary Movie aggregation tool that simplifies the  process of streaming movies by allowing users to intereact with TMDB",
          "Handled the UI development using React, Tailwind CSS, and RainbowKit.",
          "Ensured that the platform was highly secure and compliant with all relevant regulations.",
          "Worked closely with the smart contract and integration team to ensure that the platform provides most current Tv series.",
        ],
      },
    };
  },
};
</script>
