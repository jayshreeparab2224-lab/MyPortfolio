
// Mobile Navigation Menu

const menuToggle = document.getElementById("menu-toggle");
const navMenu = document.getElementById("nav-menu");

menuToggle.addEventListener("click", function () {
    navMenu.classList.toggle("active");
});

// Close menu after clicking a navigation link

const navLinks = document.querySelectorAll("#nav-menu a");

navLinks.forEach(function (link) {
    link.addEventListener("click", function () {
        navMenu.classList.remove("active");
    });
});

// Dark and Light Mode Toggle

const themeToggle = document.getElementById("theme-toggle");

themeToggle.addEventListener("click", function () {
    document.body.classList.toggle("dark-mode");

    if (document.body.classList.contains("dark-mode")) {
        themeToggle.innerHTML = '<i class="fas fa-sun"></i>';
    } else {
        themeToggle.innerHTML = '<i class="fas fa-moon"></i>';
    }
});

// Scroll Reveal Animation

const revealElements = document.querySelectorAll(
    "section, .skill-card, .project-card, .internship-card, .contact-card"
);

revealElements.forEach(function (element) {
    element.classList.add("reveal");
});

const observer = new IntersectionObserver(function (entries) {
    entries.forEach(function (entry) {
        if (entry.isIntersecting) {
            entry.target.classList.add("active");
            observer.unobserve(entry.target);
        }
    });
}, {
    threshold: 0.15
});

revealElements.forEach(function (element) {
    observer.observe(element);
});

// Contact Form Validation

const contactForm = document.getElementById("contact-form");
const formStatus = document.getElementById("form-status");

contactForm.addEventListener("submit", function (event) {

    event.preventDefault();

    const name = document.getElementById("name").value.trim();
    const email = document.getElementById("email").value.trim().toLowerCase();
    const message = document.getElementById("message").value.trim();

    if (name === "" || email === "" || message === "") {
        formStatus.textContent = "Please fill in all fields.";
        formStatus.style.color = "red";
        return;
    }

    const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

    if (!emailPattern.test(email)) {
        formStatus.textContent = "Please enter a valid email address.";
        formStatus.style.color = "red";
        return;
    }

    formStatus.textContent = "Your form has been validated successfully!";
    formStatus.style.color = "green";

    contactForm.reset();

});
