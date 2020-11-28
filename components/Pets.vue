<template>
  <section class="padded-section">
    <div class="container mx-auto text-center mb-8 lg:mb-16">
      <h2 class="text-4xl font-semibold flex justify-center items-center">
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="cat"
          class="svg-inline--fa fa-cat w-8 mr-4 text-gray-600"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
        >
          <path
            fill="currentColor"
            d="M290.59 192c-20.18 0-106.82 1.98-162.59 85.95V192c0-52.94-43.06-96-96-96-17.67 0-32 14.33-32 32s14.33 32 32 32c17.64 0 32 14.36 32 32v256c0 35.3 28.7 64 64 64h176c8.84 0 16-7.16 16-16v-16c0-17.67-14.33-32-32-32h-32l128-96v144c0 8.84 7.16 16 16 16h32c8.84 0 16-7.16 16-16V289.86c-10.29 2.67-20.89 4.54-32 4.54-61.81 0-113.52-44.05-125.41-102.4zM448 96h-64l-64-64v134.4c0 53.02 42.98 96 96 96s96-42.98 96-96V32l-64 64zm-72 80c-8.84 0-16-7.16-16-16s7.16-16 16-16 16 7.16 16 16-7.16 16-16 16zm80 0c-8.84 0-16-7.16-16-16s7.16-16 16-16 16 7.16 16 16-7.16 16-16 16z"
          ></path>
        </svg>
        <span>
          The
          <span class="text-green-600 -mr-2">"</span>
          <span class="text-red-600">Kids</span>
          <span class="text-green-600 -ml-2">"</span>
        </span>
        <svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="dog"
          class="svg-inline--fa fa-dog w-10 ml-4"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 576 512"
        >
          <path
            fill="currentColor"
            d="M298.06,224,448,277.55V496a16,16,0,0,1-16,16H368a16,16,0,0,1-16-16V384H192V496a16,16,0,0,1-16,16H112a16,16,0,0,1-16-16V282.09C58.84,268.84,32,233.66,32,192a32,32,0,0,1,64,0,32.06,32.06,0,0,0,32,32ZM544,112v32a64,64,0,0,1-64,64H448v35.58L320,197.87V48c0-14.25,17.22-21.39,27.31-11.31L374.59,64h53.63c10.91,0,23.75,7.92,28.62,17.69L464,96h64A16,16,0,0,1,544,112Zm-112,0a16,16,0,1,0-16,16A16,16,0,0,0,432,112Z"
          ></path>
        </svg>
      </h2>
    </div>
    <div class="container m-auto flex flex-wrap rounded-b-lg lg:rounded-r-lg">
      <div class="flex flex-wrap -mb-8 md:-mb-16 -mx-6">
        <div
          class="w-full md:w-1/2 lg:w-full flex flex-wrap mb-8 md:mb-16 px-6"
        >
          <div class="@MARLEY w-full lg:w-6/12 mr-auto">
            <img
              class="max-w-full rounded-t-lg lg:rounded-t-none lg:rounded-l-lg md:h-52 lg:h-auto lg:shadow-lg"
              src="~/assets/images/merj.jpeg"
              alt=""
            />
          </div>
          <div
            class="@MARLEYTEXT bg-gray-200 w-full lg:w-6/12 mx-auto flex flex-col justify-center p-8 lg:px-8 rounded-b-lg lg:rounded-b-none lg:rounded-r-lg shadow-lg"
          >
            <h3 class="font-semibold text-4xl flex items-center">Marley</h3>
            <p class="mt-8">
              Marley has had an eventful 2020. She celebrated her 6th birthday
              in January. She also went to the vet for ouchies in both her front
              ankles and she had to have a molar removed. Marley's been enjoying
              the patios here in the Twin Cities as well as our proximity to the
              river. Tony working from home has been a blessing to Marley who
              has enjoyed watching Tony work since March.
            </p>
          </div>
        </div>

        <div
          class="w-full md:w-1/2 lg:w-full flex flex-wrap mb-8 md:mb-16 px-6"
        >
          <div
            class="@DIANA w-full lg:w-6/12 lg:m-auto order-0 lg:order-1 bg-gray-200 z-50"
          >
            <img
              class="max-w-full rounded-t-lg lg:rounded-t-none lg:rounded-r-lg md:h-52 lg:h-auto shadow-lg md:-mb-24 lg:mb-auto"
              src="~/assets/images/snugdiana.jpeg"
              alt=""
            />
          </div>

          <div
            class="@DIANATEXT bg-gray-200 w-full lg:w-6/12 mx-auto flex flex-col justify-center p-8 lg:px-8 rounded-b-lg lg:rounded-b-none lg:rounded-l-lg shadow-lg z-10"
          >
            <h3 class="font-semibold text-4xl flex items-center">Diana</h3>
            <p class="mt-8">
              Diana has also had an eventful year! She celebrated her 3rd
              birthday in October. The vet told tells us that she needs to lose
              a pound or two, to her dismay. Diana has a new pastimes since we
              moved, they include chirping and threatening alleyway squirrels
              and birds, and making sure we know how hungry she is before
              sunrise.
            </p>
          </div>
        </div>
      </div>
    </div>
    <hr class="green-line" />
  </section>
</template>

<script>
export default {}
</script>

<style></style>
