# ecommerce-website-endsem
End-semester presentation for the E-commerce Website project
ShopEase is a simple and clean e-commerce website built using HTML, CSS, and JavaScript.
It includes a signup page, product display, Add-to-Cart alerts, and basic JavaScript form validation.

 Features of this website

1) Beginner-friendly design

2) Signup Page (with JavaScript validation)

3) Home Page (banner + featured products)

4) Shop Page (products with Add to Cart buttons)

5) About Page

6) Contact Page

7) Simple JavaScript validation

8) Clean CSS styling

Project Structure
→ Signup Page
→ Home Page
→ Shop Page
→ About Page
→ Contact Page
→ Stylesheet
→ JS (validation + add to cart)


Technologies Used

1) HTML5 – Structure

2) CSS3 – Styling

3) JavaScript – Form validation + alerts



JavaScript Validation Code
function form() {
    let name = document.getElementById("name").value;
    let email = document.getElementById("email").value;
    let pass = document.getElementById("pass").value;

    if (name === "") {
        alert("Please enter your name");
        return false;
    }
    if (email === "") {
        alert("Please enter your email");
        return false;
    }
    if (pass === "") {
        alert("Please enter your password");
        return false;
    }

    alert("Signup Successful!");
    return true;
}

Author : 

Aditya Sharma
Beginner Web Developer | Learning HTML, CSS, JS
