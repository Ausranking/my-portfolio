<template>
  <PortfolioPage>
    <Details :list="project" />
  </PortfolioPage>
</template>

<script>
export default {
  name: "MetamaskPage",
  layout: "portfolio",
  data() {
    return {
      project: {
        description: [
          "Responsible for building 90% of the front end with minimal supervision",
           "Implemented a custom authentication system using JWT and Redis to ensure that the platform was secure and could handle a large number of users.",
          "Set up various performance testing and monitoring tools to identify and address any bottlenecks in the system ",
        ],
        outcome: [
          "A highly efficient and scalable platform thatprovide you access to luxury and affordable houses in the metaverse, get a chance to turn your imagination to a reality at your comfort zone.",
        ],
      },
    };
  },
};
</script>
