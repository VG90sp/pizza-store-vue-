<template>
  <div class="address">
    <a
      href=""
    >
      <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M8 16C8.41061 16 8.80161 15.8244 9.0744 15.5175L9.07507 15.5168L9.07995 15.5113L9.09185 15.4977L9.09274 15.4967C9.10303 15.485 9.11734 15.4686 9.13542 15.4478C9.17159 15.4061 9.22292 15.3463 9.28725 15.2699C9.41583 15.1173 9.59678 14.8981 9.81267 14.6241C10.2432 14.0777 10.8189 13.306 11.397 12.4058C12.5046 10.6812 13.8125 8.19905 13.8125 5.86005C13.8125 2.63859 11.225 0 8 0C4.77496 0 2.1875 2.63859 2.1875 5.86005C2.1875 8.19905 3.4954 10.6812 4.60296 12.4058C5.18109 13.306 5.75676 14.0777 6.18733 14.6241C6.40322 14.8981 6.58417 15.1173 6.71275 15.2699C6.77708 15.3463 6.82842 15.4061 6.86459 15.4478C6.88266 15.4686 6.89697 15.485 6.90724 15.4967L6.91844 15.5094L6.92281 15.5144L6.9256 15.5175C7.19839 15.8244 7.58939 16 8 16ZM8 8C9.38071 8 10.5 6.88071 10.5 5.5C10.5 4.11929 9.38071 3 8 3C6.61929 3 5.5 4.11929 5.5 5.5C5.5 6.88071 6.61929 8 8 8Z" fill="#333333"/>
      </svg>
      <span class="city">{{ city }}</span>
      Круглосуточно
    </a>
    <a  href="" class="phone-number">{{ phone }}</a>
  </div>
</template>

<script>
export default {
  props: {
    city: {
      type: String,
      required: true
    },
    phone: {
      type: String,
      required: true
    }
  }
}
</script>

<style style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300;500&display=swap');

      .address {
        display: flex;
        flex-direction: column;
        padding-right: 16px;

        a {
          padding-bottom: 5px;
          text-decoration: none;
          color: #666666;
        }
        a.phone-number {
            font-family: 'Roboto Slab';
            font-style: normal;
            font-weight: 500;
            font-size: 18px;
            line-height: 24px;
            color: #000000;
          }

        svg {
          padding-right: 8px;
        }

        span {
          font-family: 'Roboto Slab';
          font-style: normal;
          font-weight: 400;
          font-size: 12px;
          line-height: 16px;
          color: #CC693E
        }
      }
</style>
