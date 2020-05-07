---
title: "Contact Us"
date: 2020-04-08T20:37:07-07:00
draft: false
weight: 1
---
<section id="form-jumbotron">
    <div class="container jumbotron">
        <p>Thank you for considering us. Give us a try, you won't regret it. We will get back to you within 24 hours.</p>
    </div>
</section>
<form action="https://formspree.io/kjwensman@lcmail.lcsc.edu" method="POST">
    <div class="form-group">
        <div class="form-row">
            <div class="col">
            <label for="first_name">First Name: *</label>
            <input id="first_name" type="text" class="form-control" placeholder="First name" name="first_name" required>
            </div>
            <div class="col">
            <label for="last_name">Last Name: *</label>
            <input type="text" id="last_name" class="form-control" placeholder="Last name" name="last_name" required>
        </div>
        </div>
    </div>
    <div class="form-group">
        <div class="form-row">
            <div class="col">
                <label for="street_address">Street Address: *</label>
                <input type="text" class="form-control" id="street_address" placeholder="Street Address" name="street_address" required>
            </div>
            <div class="col">
                <label for="street_address_line2">Street Address Line 2: </label>
                <input type="text" class="form-control" id="street_address_line2" placeholder="Street Address Line 2 (Optional)" name="street_address_line2">
            </div>
        </div>
        <div class="form-row">
            <div class="col-7">
                <label for="city">City: *</label>
                <input type="text" class="form-control" id="city" placeholder="City" name="city" required>
            </div>
            <div class="col">
                <label for="state">State: *</label>
                <input type="text" class="form-control" id="state" placeholder="State" name="state" required>
            </div>
            <div class="col">
                <label for="zip_code">Zip: *</label>
                <input id="zip_code" type="text" class="form-control" placeholder="Zip Code" name="zip_code" inputmode="numeric" pattern="^(?(^00000(|-0000))|(\d{5}(|-\d{4})))$" required>
            </div>
        </div>
    </div>
    <div class="form-group">
        <div class="form-row">
            <div class="col">
                <label for="email">Email Address *</label>
                <input type="email" class="form-control" id="email" placeholder="Enter email" name="email" required>
            </div>
            <div class="col">
                <label for="phone_number">Phone Number: *</label>
                <input type="tel" class="form-control" id="phone_number" placeholder="Phone Number" name="phone_number" required>
            </div>
        </div>
    </div>
    <div class="form-group">
        <label for="description">Description of Job: *</label>
        <textarea id="description" rows="4" cols="50" class="form-control" name="description" required></textarea>
    </div>
    <div class="text-center">
        <button type="submit" class="btn btn-primary">Submit</button>
    </div>
</form>
