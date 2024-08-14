---
layout: page
permalink: /reservations/
title: Reserve a Spot
description: Let us know you're coming!
nav: true
nav_order: 2
---
<div class="form-container">
    <form
      class="form"
      action="https://formspree.io/f/xldrnyjk"
      method="POST"
    >
      <label>
        Your email:
        <input type="email" name="email" class="form-input">
      </label>
      <label>
        Student Name:
        <input name="student" class="form-input">
      </label>
      <label>
        Class:
        <select name="class" class="form-input">
            <option value="pre-ballet">Pre-Ballet</option>
            <option value="ballet-1">Level 1 Ballet</option>
            <option value="adult">Adult Ballet</option>
        </select>
      </label>
      <label>
        Class Date:
        <input type="date" name="date" class="form-input">
      </label>
      <div class="form-check-inline">
        <input type="checkbox" name="isRegular" value="Yes" id="recurring">
        <label for="recurring" style="padding: 1em; margin-bottom: 0">Student would like to attend weekly.</label>
      </div>
      <label>
        Any thoughts?
        <textarea name="message" class="form-input"></textarea>
      </label>
      <!-- your other form fields go here -->
      <button type="submit" class="form-button">Send</button>
    </form>
</div>