<script>
export default {
data() {
    return {
    menuItems: [
        {
        text: 'Characters',
        url: '#',
        current: false,
        },
        {
        text: 'Comics',
        url: '#',
        current: true,
        },
        {
        text: 'Movies',
        url: '#',
        current: false,
        },
        {
        text: 'TV',
        url: '#',
        current: false,
        },
        {
        text: 'Games',
        url: '#',
        current: false,
        },
        {
        text: 'Collectibles',
        url: '#',
        current: false,
        },
        {
        text: 'Videos',
        url: '#',
        current: false,
        },
        {
        text: 'Fans',
        url: '#',
        current: false,
        },
        {
        text: 'News',
        url: '#',
        current: false,
        },
        {
        text: 'Shop',
        url: '#',
        current: false,
        },
    ],
    };
},
};
</script>

<template>
    <header>
      <div class="container justify-content-sb h-100">
        <div>
            <a href="#">
                <img src="../assets/img/dc-logo.png" alt="DC Logo">
            </a>
        </div>
        <nav>
          <ul>
            <li v-for="(item, index) in menuItems" :key="index">
              <a :href="item.url"><b>{{ item.text.toUpperCase() }}</b></a>
            </li>
          </ul>
        </nav>
      </div>
    </header>
</template>
  
  
<style lang="scss" scoped>

  header {
    height: 100px;
    background-color: #fff;

    img {
        height: 70px;
        width: 70px;
    }

    ul {
        list-style-type: none;
        display: flex;
      
        li {
            margin: 0 10px;

            a {
                padding: 36px 0;
                text-decoration: none;
                font-size: 12px;
                color: #000;

                &:hover {
                    color: #0282F9;
                    border-bottom: 5px solid #0282F9;
                }
            }
        }

    }

}

.justify-content-sb {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.align-items-center {
    display: flex;
    align-items: center;
}

.h-100 {
    height: 100%;
}

</style>