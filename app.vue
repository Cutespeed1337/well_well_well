<script>
export default {
  data() {
    return {
      group1: [
        {
          id: 1,
          name: "Daily Mix 1",
          img: "https://avatars.mds.yandex.net/i?id=c2b326fb2bc1235848341b8d3a217703_l-12569476-images-thumbs&n=13",
        },
        {
          id: 2,
          name: "Daily Mix 2",
          img: "https://avatars.mds.yandex.net/i?id=a070a57b5f0fb65da4adb6491d5f8492057dc6bd-9181118-images-thumbs&n=13",
        },
        {
          id: 3,
          name: "Daily Mix 3",
          img: "https://avatars.mds.yandex.net/i?id=5e149578b927e4c544798e1dea89999e412febae-12595049-images-thumbs&n=13",
        },
      ],
      group2: [
        {
          id: 1,
          name: "New Release 1",
          img: "https://i.ytimg.com/vi/F4z0CoC-71c/maxresdefault.jpg?sqp=-oaymwEmCIAKENAF8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGEYgZShlMA8=&amp;rs=AOn4CLDM3vlfHaZiik6JkSFTxV4FqBowyQ",
        },
        {
          id: 2,
          name: "New Release 2",
          img: "https://avatars.mds.yandex.net/i?id=43c741bfa72f231fa78513aa294f3636_l-5316602-images-thumbs&n=13",
        },
        {
          id: 3,
          name: "New Release 3",
          img: "https://avatars.mds.yandex.net/i?id=25501c09aacf09844f97e19abfad5b42_l-5328534-images-thumbs&n=13",
        },
      ],
    };
  },
};
</script>
<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
      <MainRelease
        :name="'FRIENDLY THUG 52 NGG'"
        :desc="'Исполнитель'"
        :img="'https://avatars.mds.yandex.net/i?id=a7036c4df376a85492f85f3ec83a9cb4_l-9149651-images-thumbs&n=13'"
      ></MainRelease>
      <AppGroup :title="'Daily Mix'" :cards="group1"></AppGroup>
      <AppGroup :title="'New Releases'" :cards="group2"></AppGroup>
    </NuxtLayout>
  </div>
</template>
<style>
* {
  padding: 0px;
  margin: 0px;
  border: none;
  font-weight: 400;
  font-style: normal;
  font-family: "Helvetica", sans-serif;
}

*,
*::before,
*::after {
  box-sizing: border-box;
}

body {
  background-color: rgb(0, 0, 49);
}
</style>
