<template>
  <div>

    <p>assets/...</p>

    <picture>
      <source
        srcset="
          assets/img/test.jpg,
          assets/img/test@2x.jpg 2x,
          assets/img/test@3x.jpg 3x
        "
        type="image/jpg"
        media="(max-width: 2000px)"
      />
      <img
        src="assets/img/test.jpg"
        srcset="
          assets/img/test@2x.jpg 2x,
          assets/img/test@3x.jpg 3x
        "
        alt="test"
      />
    </picture>

    <p>/assets/...</p>

    <picture>
      <source
        srcset="
          /assets/img/test.jpg,
          /assets/img/test@2x.jpg 2x,
          /assets/img/test@3x.jpg 3x
        "
        type="image/jpg"
        media="(max-width: 2000px)"
      />
      <img
        src="/assets/img/test.jpg"
        srcset="
          /assets/img/test@2x.jpg 2x,
          /assets/img/test@3x.jpg 3x
        "
        alt="test"
      />
    </picture>

    <p>./assets/...</p>

    <picture>
      <source
        srcset="
          ./assets/img/test.jpg,
          ./assets/img/test@2x.jpg 2x,
          ./assets/img/test@3x.jpg 3x
        "
        type="image/jpg"
        media="(max-width: 2000px)"
      />
      <img
        src="./assets/img/test.jpg"
        srcset="
          ./assets/img/test@2x.jpg 2x,
          ./assets/img/test@3x.jpg 3x
        "
        alt="test"
      />
    </picture>
  </div>
</template>
