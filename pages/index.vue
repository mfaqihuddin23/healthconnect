<template>
  <div>
    <section class="hero py-10">
      <div class="container">
        <div class="flex flex-col justify-center items-center text-center gap-6">
          <h1 class="hero-heading text-6xl">
            Healthcare at Your Fingertips
          </h1>
          <span class="subtitle text-3xl">
            Connect with certified doctors anytime, anywhere
          </span>
          <UButton label="GET started" to="" class="uppercase"></UButton>
        </div>
      </div>
    </section>
    <section class="features py-10">
      <div class="container">
        <div class="flex flex-col items-center gap-10">
          <h2 class="heading-features">
            Why Us?
          </h2>
          <div class="grid grid-cols-4 space-x-4">
            <div class="features-box flex flex-col items-center gap-6 p-3">
              <div class="icon-box bg-green-500 h-20 w-20"></div>
              <div class="txt-features">
                24/7 Access to Doctors
              </div>
            </div>
            <div class="features-box flex flex-col items-center gap-6 p-3">
              <div class="icon-box bg-green-500 h-20 w-20"></div>
              <div class="txt-features">
                Secure Video Consultations
              </div>
            </div>
            <div class="features-box flex flex-col items-center gap-6 p-3">
              <div class="icon-box bg-green-500 h-20 w-20"></div>
              <div class="txt-features">
                Electronic Prescriptions
              </div>
            </div>
            <div class="features-box flex flex-col items-center gap-6 p-3">
              <div class="icon-box bg-green-500 h-20 w-20"></div>
              <div class="txt-features">
                Canadian Healthcare Compliant
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section>
      <div class="container">
        <div class="flex flex-col">
          <UFormGroup label="Name">
            <UInput placeholder="Your Name" icon="i-heroicons-document" />
          </UFormGroup>
          <UFormGroup label="Email">
            <UInput placeholder="youremail@example.com" icon="i-heroicons-envelope" />
          </UFormGroup>
          <UFormGroup label="Phone">
            <UInput placeholder="12348923" icon="i-heroicons-phone" />
          </UFormGroup>
        </div>
      </div>
    </section>
  </div>
</template>