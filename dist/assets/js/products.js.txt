// ✅ HW CompareTech - Product List with Amazon Affiliate Links
// ✅ Affiliate ID: hwcomptech5-20

const products = [
  // 📱 SMARTPHONES
  {
    id: 'p1',
    name: 'Apple iPhone 15 Pro',
    category: 'Smartphones',
    price: '$999',
    image: 'https://m.media-amazon.com/images/I/81c50PU+FVL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=iphone+15+pro&tag=hwcomptech5-20'
  },
  {
    id: 'p2',
    name: 'Samsung Galaxy S24 Ultra',
    category: 'Smartphones',
    price: '$1199',
    image: 'https://m.media-amazon.com/images/I/71HN4P-pd5L._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=galaxy+s24+ultra&tag=hwcomptech5-20'
  },
  {
    id: 'p3',
    name: 'Google Pixel 9 Pro',
    category: 'Smartphones',
    price: '$999',
    image: 'https://m.media-amazon.com/images/I/71wyfjZ6GeL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=google+pixel+9+pro&tag=hwcomptech5-20'
  },

  // 💻 LAPTOPS
  {
    id: 'p4',
    name: 'MacBook Air M2',
    category: 'Laptops',
    price: '$1199',
    image: 'https://m.media-amazon.com/images/I/71jG+e7roXL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=macbook+air+m2&tag=hwcomptech5-20'
  },
  {
    id: 'p5',
    name: 'Dell XPS 13',
    category: 'Laptops',
    price: '$1099',
    image: 'https://m.media-amazon.com/images/I/71w4hRybGPL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=dell+xps+13+laptop&tag=hwcomptech5-20'
  },
  {
    id: 'p6',
    name: 'ASUS ROG Zephyrus G14 Gaming Laptop',
    category: 'Laptops',
    price: '$1599',
    image: 'https://m.media-amazon.com/images/I/71BZSVZkHuL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=asus+rog+g14&tag=hwcomptech5-20'
  },

  // 🎧 HEADPHONES
  {
    id: 'p7',
    name: 'Sony WH-1000XM5',
    category: 'Headphones',
    price: '$398',
    image: 'https://m.media-amazon.com/images/I/51IdLeEE5-L._AC_SX466_.jpg',
    link: 'https://www.amazon.com/s?k=sony+wh1000xm5&tag=hwcomptech5-20'
  },
  {
    id: 'p8',
    name: 'Apple AirPods Pro (2nd Gen)',
    category: 'Headphones',
    price: '$249',
    image: 'https://m.media-amazon.com/images/I/61SUj2aKoEL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=airpods+pro+2&tag=hwcomptech5-20'
  },
  {
    id: 'p9',
    name: 'Bose QuietComfort 45',
    category: 'Headphones',
    price: '$329',
    image: 'https://m.media-amazon.com/images/I/51Ip2O0YxPL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=bose+quietcomfort+45&tag=hwcomptech5-20'
  },

  // 🎮 GAMING CONSOLES
  {
    id: 'p10',
    name: 'PlayStation 5 Console',
    category: 'Gaming Consoles',
    price: '$499',
    image: 'https://m.media-amazon.com/images/I/51OSCYlj3xL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=playstation+5&tag=hwcomptech5-20'
  },
  {
    id: 'p11',
    name: 'Xbox Series X',
    category: 'Gaming Consoles',
    price: '$499',
    image: 'https://m.media-amazon.com/images/I/61JGKhqxHxL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=xbox+series+x&tag=hwcomptech5-20'
  },
  {
    id: 'p12',
    name: 'Nintendo Switch OLED',
    category: 'Gaming Consoles',
    price: '$349',
    image: 'https://m.media-amazon.com/images/I/71wM9ANqnqL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=nintendo+switch+oled&tag=hwcomptech5-20'
  },

  // ⌚ SMARTWATCHES
  {
    id: 'p13',
    name: 'Apple Watch Series 9',
    category: 'Smartwatches',
    price: '$399',
    image: 'https://m.media-amazon.com/images/I/71Z0O4cWIEL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=apple+watch+series+9&tag=hwcomptech5-20'
  },
  {
    id: 'p14',
    name: 'Samsung Galaxy Watch 6',
    category: 'Smartwatches',
    price: '$299',
    image: 'https://m.media-amazon.com/images/I/71o2Po9triL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=galaxy+watch+6&tag=hwcomptech5-20'
  },

  // 📺 TVs & MONITORS
  {
    id: 'p15',
    name: 'Samsung 55" 4K Smart TV',
    category: 'TVs',
    price: '$599',
    image: 'https://m.media-amazon.com/images/I/71RiQZ0T8QL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=samsung+55+inch+4k+tv&tag=hwcomptech5-20'
  },
  {
    id: 'p16',
    name: 'LG 48" OLED Smart TV',
    category: 'TVs',
    price: '$999',
    image: 'https://m.media-amazon.com/images/I/71Ydpx5ZTAL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=lg+oled+tv&tag=hwcomptech5-20'
  },
  {
    id: 'p17',
    name: 'ASUS 27" 165Hz Gaming Monitor',
    category: 'Monitors',
    price: '$299',
    image: 'https://m.media-amazon.com/images/I/81zA4F6I8zL._AC_SX522_.jpg',
    link: 'https://www.amazon.com/s?k=asus+gaming+monitor&tag=hwcomptech5-20'
  }
];

// Make available globally
window.products = products;
