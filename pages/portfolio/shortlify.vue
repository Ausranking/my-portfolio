<template>
    <PortfolioPage>
        <Details :list="project" />
    </PortfolioPage>
</template>

<script>
export default {
    name: "Shortlify ",
    layout: "portfolio",
    data() {
        return {
            project: {
                outcome: [
                    "Shortlify is a user-friendly web application designed to simplify the sharing of web links. It empowers users to convert lengthy URLs into short, easy-to-remember links, enhancing accessibility and convenience. With the added feature of one-click copying to the clipboard, sharing online content has never been easier. Shortlify streamlines the web experience, making the internet more accessible and user-centric.",
                ],
                description: [
                    "Responsible for developing the user interface and user                   experience of Shortlify. This included creating the input forms for URL submission, designing the interface for displaying the shortened links, and implementing the one-click copy-to-clipboard functionality.",

                    "Handled the UI development using React, Tailwind CSS, and Redux.",

                    "I integrated a URL shortening service, allowing users to submit URLs and receive shortened versions. This involved testing several and finally integrated a unique API to ensure the functionality worked seamlessly.",

                    "As a solo developer on this project, I took on project management responsibilities, including setting project milestones, managing timelines, and ensuring that the development process was on track.",
                ],
            },
        };
    },
};
</script>
