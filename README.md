<!DOCTYPE html>
<meta charset="UTF-8">
1. Personal Information Section
Html<form>
  <fieldset>
    <legend>Personal Information</legend>
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required placeholder="Full Name"><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>

    <label for="phone">Phone Number:</label>
    <input type="tel" id="phone" name="phone"><br><br>
  </fieldset>
</form>


2. Address Section
Html<form>
  <fieldset>
    <legend>Address</legend>
    <label for="street">Street Address:</label>
    <input type="text" id="street" name="street" required><br><br>

    <label for="city">City:</label>
    <input type="text" id="city" name="city" required><br><br>

    <label for="state">State:</label>
    <input type="text" id="state" name="state" required><br><br>

    <label for="zip">Zip Code:</label>
    <input type="text" id="zip" name="zip" required><br><br>
  </fieldset>
</form>


3. Feedback Section
Html<form>
  <fieldset>
    <legend>Feedback</legend>
    <label for="rating">Rate Us:</label>
    <select id="rating" name="rating">
      <option value="excellent">Excellent</option>
      <option value="good">Good</option>
      <option value="average">Average</option>
      <option value="poor">Poor</option>
    </select><br><br>

    <label for="comments">Comments:</label><br>
    <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br><br>
  </fieldset>
</form>


4. Submit Button
Html<form>
  <button type="submit">Submit</button>
</form>


You can combine these sections into a single form or use them independently based on your requirements. Each section is wrapped in a <fieldset> for better organization and accessibility.
