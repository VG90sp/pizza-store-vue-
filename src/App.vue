<template>
  <div class="page">
    <header class="page__header">
      <div class="page__header-logo">
        <svg width="225" height="70" viewBox="0 0 225 70" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
          <rect x="-5.05615" y="-6.7476" width="246.91" height="80.9639" fill="url(#pattern0)"/>
          <defs>
          <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
            <use xlink:href="#image0_841_22377" transform="translate(-0.027225) scale(0.00321479 0.00980392)"/>
          </pattern>
            <image id="image0_841_22377" width="328" height="102" xlink:href="data:image/png;base64,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"/>
</defs>
        </svg>
      </div>
      <div class="page__header__addresses">
        <address-block
          city="Ховрино"
          phone="+7(495) 980-66-22"
        />
        <address-block
        city="Измайлово"
        phone="+7(495) 730-55-66"
        />
        <address-block
        city="Мытищи"
        phone="+7(495) 500-40-40"
        />
        <address-block
        city="Хор.-Мневники"
        phone="+7(495) 980-66-22"
        />
      </div>
      <div class="page__header__burger__menu">
        <hamburger-menu />
      </div>
    </header>
    <main class="page__main">
      <div class="page__main__icons">
        <div class="page__main__icons__phone">
          <button class="btn_phone">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M4.94159 0.0975844C5.37299 -0.118118 5.89774 0.0346889 6.14589 0.448277L9.46885 5.98654C9.71083 6.38985 9.61073 6.91015 9.23756 7.19504L7.67238 8.42818C7.34343 8.68734 7.24476 9.11105 7.40679 9.44533C8.92628 12.5802 11.4783 15.0861 14.5533 16.5881C14.889 16.7521 15.3149 16.6536 15.5749 16.3236L16.805 14.7624C17.0899 14.3893 17.6102 14.2892 18.0135 14.5312L23.5517 17.8541C23.9653 18.1023 24.1181 18.627 23.9024 19.0584L21.6871 23.489C21.5308 23.8017 21.2111 23.9993 20.8615 23.9993C9.57912 23.9993 0.424925 14.819 0.0150602 3.38563C0.014408 3.36744 0.0135383 3.35923 0.0119519 3.34425C0.0103864 3.32947 0.00812318 3.3081 0.00468251 3.26406C-0.000185368 3.20174 -0.00579664 3.0998 0.0136125 2.98483C0.0214856 2.93819 0.0329764 2.89197 0.0481025 2.84659C0.125517 2.61435 0.292019 2.42237 0.510981 2.31289L4.94159 0.0975844Z" fill="white"/>
            </svg>
           </button>
        </div>
        <div class="page__main__icons__location">
          <button class="btn_location">
            <svg width="24" height="24" viewBox="0 0 18 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M9 24C9.61591 24 10.2024 23.7366 10.6116 23.2763L10.6126 23.2752L10.6199 23.2669L10.6378 23.2466L10.6391 23.2451C10.6545 23.2275 10.676 23.203 10.7031 23.1717C10.7574 23.1091 10.8344 23.0194 10.9309 22.9049C11.1237 22.676 11.3952 22.3471 11.719 21.9362C12.3649 21.1165 13.2284 19.959 14.0956 18.6087C15.7569 16.0219 17.7188 12.2986 17.7188 8.79007C17.7188 3.95789 13.8376 0 9 0C4.16244 0 0.28125 3.95789 0.28125 8.79007C0.28125 12.2986 2.24309 16.0219 3.90444 18.6087C4.77163 19.959 5.63514 21.1165 6.281 21.9362C6.60484 22.3471 6.87626 22.676 7.06912 22.9049C7.16562 23.0194 7.24264 23.1091 7.29688 23.1717C7.32399 23.203 7.34545 23.2275 7.36086 23.2451L7.37765 23.2642L7.38422 23.2716L7.3884 23.2763C7.79758 23.7366 8.38409 24 9 24ZM9 12C11.0711 12 12.75 10.3211 12.75 8.25C12.75 6.17893 11.0711 4.5 9 4.5C6.92893 4.5 5.25 6.17893 5.25 8.25C5.25 10.3211 6.92893 12 9 12Z" fill="white"/>
            </svg>
          </button>
        </div>
        <div class="page__main__icons__user">
          <button class="btn_user">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M0 12C0 5.37258 5.37258 0 12 0C18.6274 0 24 5.37258 24 12C24 18.6274 18.6274 24 12 24C5.37258 24 0 18.6274 0 12ZM12 2.66667C6.84534 2.66667 2.66667 6.84534 2.66667 12C2.66667 17.1547 6.84534 21.3333 12 21.3333C17.1547 21.3333 21.3333 17.1547 21.3333 12C21.3333 6.84534 17.1547 2.66667 12 2.66667Z" fill="white"/>
<path d="M15.75 8.25C15.75 10.3211 14.0711 12 12 12C9.92893 12 8.25 10.3211 8.25 8.25C8.25 6.17893 9.92893 4.5 12 4.5C14.0711 4.5 15.75 6.17893 15.75 8.25Z" fill="white"/>
<path d="M5.31777 15.4091C6.55917 13.8306 9.08543 12.75 12 12.75C14.9145 12.75 17.4408 13.8306 18.6822 15.4091C17.4408 17.8375 14.9145 19.5 12 19.5C9.08542 19.5 6.55916 17.8375 5.31777 15.4091Z" fill="white"/>
            </svg>
          </button>
        </div>
        <div class="page__main__icons__price">
          <button class="btn_price">
            <svg width="24" height="24" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M0 1.875C0 1.18464 0.559644 0.625 1.25 0.625H3C4.66463 0.625 5.5734 1.68641 5.99782 2.55991C6.08578 2.74093 6.15677 2.91934 6.21412 3.08738H18.75C19.1094 3.08738 19.4515 3.2421 19.6888 3.51204C19.9261 3.78198 20.0357 4.14101 19.9897 4.49748L19.0564 11.7247C18.9759 12.348 18.4451 12.8146 17.8167 12.8146H6.15C6.13986 12.8146 6.13264 12.8152 6.12785 12.8158C6.12424 12.8195 6.11896 12.8255 6.11226 12.8348C6.06419 12.9011 6 13.0586 6 13.2823C6 13.506 6.06419 13.6635 6.11226 13.7299C6.11896 13.7391 6.12425 13.7452 6.12785 13.7489C6.13265 13.7495 6.13986 13.75 6.15 13.75H17.6667C18.357 13.75 18.9167 14.3096 18.9167 15C18.9167 15.6904 18.357 16.25 17.6667 16.25H6.15C5.24462 16.25 4.53297 15.8111 4.08774 15.1966C3.66915 14.6188 3.5 13.9174 3.5 13.2823C3.5 12.6472 3.66915 11.9458 4.08774 11.368C4.27526 11.1092 4.51004 10.8816 4.78664 10.7047C4.63028 9.4359 4.45493 8.08305 4.30738 6.96454C4.21368 6.25418 4.13134 5.63944 4.07244 5.20236C4.04299 4.98383 4.01941 4.80976 4.00319 4.69039L3.97819 4.50673C3.97495 4.48303 3.97239 4.45921 3.97051 4.43537L3.97029 4.43309C3.9697 4.42712 3.96827 4.41359 3.96566 4.39363C3.96039 4.35335 3.95061 4.28904 3.93385 4.20914C3.89918 4.04373 3.84071 3.8408 3.7492 3.65247C3.57541 3.29479 3.37585 3.125 3 3.125H1.25C0.559644 3.125 0 2.56536 0 1.875ZM6.6465 5.58738C6.68846 5.90152 6.73555 6.2558 6.78591 6.6376C6.93052 7.73383 7.10244 9.0596 7.25747 10.3146H16.7177L17.3282 5.58738H6.6465ZM6.13339 12.8107L6.13254 12.8113L6.13339 12.8107Z" fill="white"/>
<circle cx="16.5625" cy="18.4375" r="1.5625" fill="white"/>
<circle cx="7.8125" cy="18.4375" r="1.5625" fill="white"/>
            </svg>
            <span>4888 ₽</span>
          </button>
        </div>
      </div>
      <breadcrumds-block />
        <div class="page__main__products">
        <product-block
        product_name="Чизбургер барбекю"
        product_text="Соус коктейль, фарш из отборной говядины, маринованные огурцы, спелые томаты, сыр моцарелла, сыр чеддер, соус барбекю, хрустящий лук"
        price=888
        image="https://i.postimg.cc/Jyj82t6t/image-1.jpg"
        image_mobile="https://i.ibb.co/nbqZwyD/image-1.jpg"
        />
        <product-block
        product_name="Суприм"
        product_text="Соус томатный, сыр моцарелла, колбаса пепперони, ветчина, лук, сладкий перец, грибной микс, свинина, говядина, оливки черные"
        price=690
        novel= true
        image= "https://i.postimg.cc/5Y1Jd1Tg/image-2.jpg"
        image_mobile="https://i.ibb.co/hB622jj/image-mob-2.jpg"
        />
        <product-block
        product_name="Бургер «Два сыра»"
        product_text="Ароматная котлета из мраморной говядины с сыром чеддер и моцарелла, хрустящим луком, маринованными корнишонами, свежими томатами, соусом коктейль и барбекю в мягкой пшеничной булочке. Картофель и соус приобретается отдельно"
        price=180
        novel= true
        image= "https://i.postimg.cc/K3x8NtmZ/image-3.jpg"
        image_mobile="https://i.ibb.co/QmR35bc/image-mob-3.jpg"
        />
        <product-block
        product_name="Суши Унаги»"
        product_text="Угорь"
        price=120
        novel= true
        image="https://i.postimg.cc/ZvHKD0q6/image-4.jpg"
        image_mobile="https://i.ibb.co/sv0VM06/image-mob-4.jpg"
        />
        <product-block
        product_name="Умэ"
        product_text="Лосось, угорь, сыр «Филадельфия», авокадо"
        price=385
        novel= true
        image="https://i.postimg.cc/Sjh655sK/image-5.jpg"
        image_mobile="https://i.ibb.co/PGTX5s9/image-mob-5.jpg"
        />
        </div>
        <div class="page__main__present">
        <h2 class="title">Подарки</h2>
        <present-block
        product_name='Морс "Смородина"'
        product_text='Морс "Смородина", 1 л'
        present= true
        image_mobile="https://i.ibb.co/HBxmjR5/image-present-mob.jpg"
         />
        </div>
        <aside class="page__main__aside">
          <sidebar-block />
        </aside>
      <div class="page__main__recommend">
        <h2 class="title">Рекомендуем</h2>
        <div class="page__main__recommend__products">
          <recommend-block
            product_name='Чизбургер барбекю'
            product_text='Соус коктейль, фарш из отборной говядины, маринованные огурцы, спелые томаты, сыр моцарелла, сыр чеддер, соус барбекю, хрустящий лук'
            price="от 287 ₽"
            from_sum= true
            image_rec="https://i.postimg.cc/K4tkdSvH/image-rec-1.jpg"
          />
           <recommend-block
            product_name='Бургер «Два сыра»'
            product_text='Ароматная котлета из мраморной говядины с сыром чеддер и моцарелла, хрустящим луком, маринованными корнишонами, свежими томатами, соусом коктейль и барбекю в мягкой пшеничной булочке. Картофель и соус приобретается отдельно'
            price="387 ₽"
            novel= true
            image_rec="https://i.postimg.cc/0bxMvWz2/image-rec-2.jpg"
          />
            <recommend-block
            product_name='Суши Эби'
            product_text='Креветка'
            price="130 ₽"
            novel= true
            image_rec="https://i.postimg.cc/jLs5mD1D/image-rec-3.jpg"
          />
          <recommend-block
            product_name='Чизбургер барбекю'
            product_text='Соус коктейль, фарш из отборной говядины, маринованные огурцы, спелые томаты, сыр моцарелла, сыр чеддер, соус барбекю, хрустящий лук'
            price="от 287 ₽"
            from_sum= true
            image_rec="https://i.postimg.cc/K4tkdSvH/image-rec-1.jpg"
          />
          <recommend-block
            product_name='Бургер «Два сыра»'
            product_text='Ароматная котлета из мраморной говядины с сыром чеддер и моцарелла, хрустящим луком, маринованными корнишонами, свежими томатами, соусом коктейль и барбекю в мягкой пшеничной булочке. Картофель и соус приобретается отдельно'
            price="387 ₽"
            novel= true
            image_rec="https://i.postimg.cc/0bxMvWz2/image-rec-2.jpg"
          />
           <recommend-block
            product_name='Суши Эби'
            product_text='Креветка'
            price="130 ₽"
            novel= true
            image_rec="https://i.postimg.cc/jLs5mD1D/image-rec-3.jpg"
          />
        </div>
      </div>
      <div class="page__main__total">
        <total-block
        sale_price= 4200
        total_price= "3580 ₽"
        />
      </div>
    </main>
    <footer class="page__footer">
      <footer-block />
    </footer>
  </div>
</template>

<script>
import AddressBlock from '@/components/AddressBlock.vue'
import BreadcrumdsBlock from '@/components/BreadcrumbsBlock.vue'
import ProductBlock from '@/components/ProductBlock.vue'
import PresentBlock from '@/components/PresentBlock.vue'
import RecommendBlock from '@/components/RecommendBlock.vue'
import TotalBlock from '@/components/TotalBlock.vue'
import SidebarBlock from '@/components/SidebarBlock.vue'
import FooterBlock from '@/components/FooterBlock.vue'
import HamburgerMenu from '@/components/HamburgerMenu.vue'

export default {
  components: {
    AddressBlock,
    BreadcrumdsBlock,
    ProductBlock,
    PresentBlock,
    RecommendBlock,
    TotalBlock,
    SidebarBlock,
    FooterBlock,
    HamburgerMenu
  },

  data () {
    return {
      city: '',
      phone: '',
      product_name: '',
      product_text: '',
      price: ''
    }
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300;500&display=swap');

@media(min-width: 961px) {
 .page {
  &__header {
    display: flex;
    margin: 40px 64px 80px 64px;
    max-width: 100%;

    &-logo>svg {
      width: 225px;
      height: 70px;
    }

    &__addresses {
      display: flex;
      margin-left: 8%;
      width: 100%;
      justify-content: space-between;
    }
    &__burger__menu {
      display: none;
    }
  }
  &__main {
     position: relative;
    margin: 0 64px 0px 64px;
    display: flex;
    max-width: 100%;
    flex-direction: column;

          .title {
        margin: 67px 0 0 0;
        font-family: 'Roboto Slab';
        font-style: normal;
        font-weight: 700;
        font-size: 30px;
        line-height: 44px;
        color: black
      }

      &__recommend__products {
        display:flex;
        flex-direction: row;
        flex-wrap: nowrap;
        overflow-x: auto;
        border-bottom: 2px solid #B3B3B3;
        padding-bottom: 64px;
      }

      &__total {
        display: flex;
        margin: 32px 0 70px 0;
        justify-content: flex-end;
      }

      &__aside {
            content: "";
            position: absolute;
            left: 62%;
            top:84px
      }

      &__icons {
        display: none;
      }
  }

  &__footer {
    background: black;
    padding: 32px 64px 32px 64px;
  }
 }
}

@media(max-width: 479px) {
 body {
   margin: 0;

  .page__header {
    margin: 16px;
    display: flex;

  &-logo>svg {
    width: 145px;
    height: 45px;
  }
  &__addresses {
    display: none;
  }
  &__burger__menu {
    display: flex;
    margin-left: auto;
      }
  }
  .page__main {
    margin: 0;
      &__icons {
        display: flex;
        justify-content: space-between;

        .btn_phone {
          width: 57px;
          height: 40px;
          background: #333333;
          border-radius: 0px 25px 25px 0px;
        }

        .btn_location {
          width: 57px;
          height: 40px;
          background: #333333;
          border-radius: 25px;
        }
        .btn_user {
          width: 57px;
          height: 40px;
          background: #333333;
          border-radius: 25px;
        }
        .btn_price {
          display: flex;
          height: 40px;
          background: #CC693E;
          border-radius: 25px 0px 0px 25px;
          align-items: center;
          padding: 10px 26px 10px 26px;

          span {
            padding-left: 8px;
            font-family: 'Roboto Slab';
            font-style: normal;
            font-weight: 700;
            font-size: 14px;
            line-height: 20px;
            color: #FFFFFF;
          }
        }
      }

      &__present {
        h2 {
          font-family: 'Roboto Slab';
          font-style: normal;
          font-weight: 700;
          font-size: 20px;
          line-height: 28px;
          margin-left: 16px;
        }
      }

      &__recommend {
        display: none;
      }

      &__total {
        display: none;
      }
  }
}
}
</style>
