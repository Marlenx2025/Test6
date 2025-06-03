# Test6
Test6

<!DOCTYPE html>
<html lang="en">

<header>
  
  body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background-color: #faf9f6;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #1C1F2B;
  padding: 20px 40px;
}

.logo {
  font-size: 24px;
  color: #E1C699;
  font-weight: bold;
  font-family: 'Playfair Display', serif;
}

.nav-links {
  list-style: none;
  display: flex;
  align-items: center;
  gap: 25px;
}

.nav-links li {
  position: relative;
}

.nav-links a {
  color: #ffffff;
  text-decoration: none;
  font-size: 16px;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #D4AF7F;
}

.cta {
  background-color: #D4AF7F;
  color: #1C1F2B;
  padding: 8px 16px;
  border-radius: 4px;
  font-weight: bold;
}

.cta:hover {
  background-color: #e1c699;
}

.dropdown-menu {
  display: none;
  position: absolute;
  background-color: #1C1F2B;
  padding: 10px 0;
  top: 35px;
  left: 0;
  min-width: 180px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
}

.dropdown-menu li {
  padding: 8px 16px;
}

.dropdown-menu a {
  color: #ffffff;
  font-size: 14px;
}

.dropdown:hover .dropdown-menu {
  display: block;
}

  
    <nav class="navbar">
    <div class="logo">Marlenx</div>
    <ul class="nav-links">
      <li><a href="#">Home</a></li>
      <li class="dropdown">
        <a href="#">Features</a>
        <ul class="dropdown-menu">
          <li><a href="#">Scheduling</a></li>
          <li><a href="#">Payments</a></li>
          <li><a href="#">Client Management</a></li>
          <li><a href="#">Staff & Payroll</a></li>
        </ul>
      </li>
      <li><a href="#">Pricing</a></li>
      <li class="dropdown">
        <a href="#">For Who</a>
        <ul class="dropdown-menu">
          <li><a href="#">Soccer Coaches</a></li>
          <li><a href="#">Yoga Instructors</a></li>
          <li><a href="#">Trainers</a></li>
        </ul>
      </li>
      <li><a href="#">Resources</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
      <li><a href="#">Login</a></li>
      <li><a class="cta" href="#">Start Free Trial</a></li>
    </ul>
  </nav>
</header>
