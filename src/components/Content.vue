<template>
  <div class="bg-white overflow-hidden">
    <div class="relative max-w-7xl mx-auto py-16 px-4 sm:px-6 lg:px-8">
      <div
        class="
          hidden
          lg:block
          bg-gray-50
          absolute
          top-0
          bottom-0
          left-3/4
          w-screen
        "
      ></div>
      <div
        class="
          mx-auto
          text-base
          max-w-prose
          lg:grid lg:grid-cols-2 lg:gap-8 lg:max-w-none
        "
      >
        <div>
          <h3
            class="
              mt-2
              text-3xl
              leading-8
              font-extrabold
              tracking-tight
              text-gray-900
              sm:text-4xl
            "
          >
            Meet Ridge Kimani
          </h3>
        </div>
      </div>
      <div class="mt-8 lg:grid lg:grid-cols-2 lg:gap-8">
        <div class="relative lg:row-start-1 lg:col-start-2">
          <svg
            class="hidden lg:block absolute top-0 right-0 -mt-20 -mr-20"
            width="404"
            height="384"
            fill="none"
            viewBox="0 0 404 384"
            aria-hidden="true"
          >
            <defs>
              <pattern
                id="de316486-4a29-4312-bdfc-fbce2132a2c1"
                x="0"
                y="0"
                width="20"
                height="20"
                patternUnits="userSpaceOnUse"
              >
                <rect
                  x="0"
                  y="0"
                  width="4"
                  height="4"
                  class="text-gray-200"
                  fill="currentColor"
                />
              </pattern>
            </defs>
            <rect
              width="404"
              height="384"
              fill="url(#de316486-4a29-4312-bdfc-fbce2132a2c1)"
            />
          </svg>
          <ContentImage />
        </div>
        <div class="mt-8 lg:mt-0">
          <div class="text-base max-w-prose mx-auto lg:max-w-none">
            <p class="text-lg text-gray-500">
              I'm a tech enthusiast and I build software for the internet. I
              ensure that products built are of high standards, maintainable and
              sustainable in the market. I love being a team player. It makes me
              grow as a leader and a software engineer at large. I'm also a
              research scientist who's trying to bring knowledge of hidden
              reality to the world. My works relate to quantum physics and
              string theory and my vision is to bring the year 3000 this century
              :)
            </p>
          </div>
          <div
            class="
              mt-5
              prose prose-indigo
              text-gray-500
              mx-auto
              lg:max-w-none lg:row-start-1 lg:col-start-1
            "
          >
            <h3 class="text-3xl">Dev in progress ...</h3>

            <h3 class="text-3xl">Work History</h3>
            <span>1. Afristellar Nairobi, Kenya Mar 2021 - Current</span>

            <p>
              Afristellar is a dream to the world in which we want to take
              Africa and the world beyond to interstellar space. This requires a
              lot of knowledge to be presented to the world so that the dream
              can become a reality. Therefore at this point in time, we host a
              podcast where we talk about contemporary issues that are facing
              the world at the same time talking about the physics and the
              science of the day today. As a research scientist here I also do
              independent research on the current trends and collaborate in
              helping science pioneers in realizing futuristic scientific
              dreams.
            </p>
            <p>
              Accomplishments 1. Collaborating in scientific papers. Currently,
              at Academia I have over 500 mentions in different scientific
              fields. Some of the papers include mentions in Artificial
              Intelligence. 2. Spearheading research on quantum mechanics.
              Through experiments and research, I have been able to discover and
              see how classical physics relates to the small infinitesimal units
              of life(quantum). 3. Starting an Afristellar school using Google
              Classroom. This is still a work in progress but the main idea is
              to provide free science education for all. This will spark the
              curiosity of future scientists.
            </p>
            <h3>Education and Learning</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ContentImage from '@/components/ContentImage'
export default {
  name: 'Content',
  components: { ContentImage }
}
</script>

<style scoped></style>
