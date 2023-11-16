// Define variables for reusability
$primary-color: #007bff;
$secondary-color: #cc1b1b;

// Import Bootstrap SCSS
@import "bootstrap";

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: rgb(244, 245, 245);

  @media screen and (max-width: 768px) {
    font-size: 16px;
  }
}

header {
  background-color: rgb(71, 20, 82);
  color: #fff;
  text-align: center;
  padding: 2rem 0;

  h1 {
    margin-bottom: 0.5rem;
    font-size: 2.5rem;
  }

  p {
    font-size: 1.2rem;
  }
}

section {
  padding: 2rem;
}

section h2 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
}

section p {
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
}

section ul {
  list-style-type: disc;
  margin-left: 1.5rem;
}

section li {
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}

a {
  color: $primary-color;
  text-decoration: none;

  &:hover {
    text-decoration: underline;
  }
}

footer {
  background-color: $secondary-color;
  text-align: center;
  padding: 1rem 0;
}
