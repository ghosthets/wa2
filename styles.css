let currentIndex = 0;
const products = document.querySelectorAll('.product-cart');
const totalProducts = products.length;

const prevBtn = document.getElementById('prevBtn');
const nextBtn = document.getElementById('nextBtn');
const productCarousel = document.getElementById('productCarousel');

function updateCarousel() {
    const offset = -currentIndex * (products[0].offsetWidth + 10); // Add gap size
    productCarousel.style.transform = `translateX(${offset}px)`;
}

prevBtn.addEventListener('click', () => {
    if (currentIndex > 0) {
        currentIndex--;
        updateCarousel();
    }
});

nextBtn.addEventListener('click', () => {
    if (currentIndex < totalProducts - 1) {
        currentIndex++;
        updateCarousel();
    }
});
