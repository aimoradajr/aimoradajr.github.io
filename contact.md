---
layout: plain
title: Contact
---

<h2 style="text-align: center">Contact Me</h2>
<p style="text-align: center">Feel free to reach out using the form below. I'll get back to you as soon as possible.</p>

<form action="https://formspree.io/f/xvggvale" method="POST" class="neobrutalist-form">

<label for="name" class="form-label">Project:</label>
<input type="text" id="project" name="project" value="" class="form-input" style="background-color: #ffecc8" readonly>

<label for="name" class="form-label">Your Name:</label>
<input type="text" id="name" name="name" class="form-input" required>

<label for="email" class="form-label">Your Email:</label>
<input type="email" id="email" name="_replyto" class="form-input" required>

<label for="message" class="form-label">Your Message:</label>
<textarea id="message" name="message" rows="5" class="form-textarea" style="resize: vertical" required></textarea>

<button type="submit" class="form-button">Send</button>

</form>

<script>
  // Get URL parameters
  const urlParams = new URLSearchParams(window.location.search);
  const projectName = urlParams.get('project');

  // Set the hidden field value if "project" parameter exists
  if (projectName) {
    document.getElementById('project').value = projectName;
  }
</script>

<style>
	
:root {
  --text-color: #495057;
  --text-color-secondary: #6c757d;
  --border-radius: 6px;
  --primary-color: #3b82f6;
  --primary-color-text: #ffffff;
  --surface-ground: #eff3f8;
  --surface-section: #ffffff;
  --surface-card: #ffffff;
  --surface-overlay: #ffffff;
  --surface-border: #dfe7ef;
  --surface-hover: #f6f9fc;
  --surface-0: #ffffff;
  --surface-50: #fafafa;
  --surface-100: #f5f5f5;
  --surface-200: #eeeeee;
  --surface-300: #e0e0e0;
  --surface-400: #bdbdbd;
  --surface-500: #9e9e9e;
  --surface-600: #757575;
  --surface-700: #616161;
  --surface-800: #424242;
  --surface-900: #212121;
  --blue-50: #f5f9ff;
  --blue-100: #d0e1fd;
  --blue-200: #abc9fb;
  --blue-300: #85b2f9;
  --blue-400: #609af8;
  --blue-500: #3b82f6;
  --blue-600: #326fd1;
  --blue-700: #295bac;
  --blue-800: #204887;
  --blue-900: #183462;
  --green-50: #f4fcf7;
  --green-100: #caf1d8;
  --green-200: #a0e6ba;
  --green-300: #76db9b;
  --green-400: #4cd07d;
  --green-500: #22c55e;
  --green-600: #1da750;
  --green-700: #188a42;
  --green-800: #136c34;
  --green-900: #0e4f26;
  --yellow-50: #fefbf3;
  --yellow-100: #faedc4;
  --yellow-200: #f6de95;
  --yellow-300: #f2d066;
  --yellow-400: #eec137;
  --yellow-500: #eab308;
  --yellow-600: #c79807;
  --yellow-700: #a47d06;
  --yellow-800: #816204;
  --yellow-900: #5e4803;
  --cyan-50: #f3fbfd;
  --cyan-100: #c3edf5;
  --cyan-200: #94e0ed;
  --cyan-300: #65d2e4;
  --cyan-400: #35c4dc;
  --cyan-500: #06b6d4;
  --cyan-600: #059bb4;
  --cyan-700: #047f94;
  --cyan-800: #036475;
  --cyan-900: #024955;
  --pink-50: #fef6fa;
  --pink-100: #fad3e7;
  --pink-200: #f7b0d3;
  --pink-300: #f38ec0;
  --pink-400: #f06bac;
  --pink-500: #ec4899;
  --pink-600: #c93d82;
  --pink-700: #a5326b;
  --pink-800: #822854;
  --pink-900: #5e1d3d;
  --indigo-50: #f7f7fe;
  --indigo-100: #dadafc;
  --indigo-200: #bcbdf9;
  --indigo-300: #9ea0f6;
  --indigo-400: #8183f4;
  --indigo-500: #6366f1;
  --indigo-600: #5457cd;
  --indigo-700: #4547a9;
  --indigo-800: #363885;
  --indigo-900: #282960;
  --teal-50: #f3fbfb;
  --teal-100: #c7eeea;
  --teal-200: #9ae0d9;
  --teal-300: #6dd3c8;
  --teal-400: #41c5b7;
  --teal-500: #14b8a6;
  --teal-600: #119c8d;
  --teal-700: #0e8174;
  --teal-800: #0b655b;
  --teal-900: #084a42;
  --orange-50: #fff8f3;
  --orange-100: #feddc7;
  --orange-200: #fcc39b;
  --orange-300: #fba86f;
  --orange-400: #fa8e42;
  --orange-500: #f97316;
  --orange-600: #d46213;
  --orange-700: #ae510f;
  --orange-800: #893f0c;
  --orange-900: #642e09;
  --bluegray-50: #f7f8f9;
  --bluegray-100: #dadee3;
  --bluegray-200: #bcc3cd;
  --bluegray-300: #9fa9b7;
  --bluegray-400: #818ea1;
  --bluegray-500: #64748b;
  --bluegray-600: #556376;
  --bluegray-700: #465161;
  --bluegray-800: #37404c;
  --bluegray-900: #282e38;
  --purple-50: #fbf7ff;
  --purple-100: #ead6fd;
  --purple-200: #dab6fc;
  --purple-300: #c996fa;
  --purple-400: #b975f9;
  --purple-500: #a855f7;
  --purple-600: #8f48d2;
  --purple-700: #763cad;
  --purple-800: #5c2f88;
  --purple-900: #432263;
  --red-50: #fff5f5;
  --red-100: #ffd0ce;
  --red-200: #ffaca7;
  --red-300: #ff8780;
  --red-400: #ff6259;
  --red-500: #ff3d32;
  --red-600: #d9342b;
  --red-700: #b32b23;
  --red-800: #8c221c;
  --red-900: #661814;
  --primary-50: #f5f9ff;
  --primary-100: #d0e1fd;
  --primary-200: #abc9fb;
  --primary-300: #85b2f9;
  --primary-400: #609af8;
  --primary-500: #3b82f6;
  --primary-600: #326fd1;
  --primary-700: #295bac;
  --primary-800: #204887;
  --primary-900: #183462;
  --gray-50: #fafafa;
  --gray-100: #f5f5f5;
  --gray-200: #eeeeee;
  --gray-300: #e0e0e0;
  --gray-400: #bdbdbd;
  --gray-500: #9e9e9e;
  --gray-600: #757575;
  --gray-700: #616161;
  --gray-800: #424242;
  --gray-900: #212121;
  color-scheme: light;
}
	/* Brutalist Form Styling */
.neobrutalist-form {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  max-width: 600px;
  margin: 2rem auto;
  background-color: #fff; /* Card background */
  padding: 2rem;
  border: 3px solid #000; /* Bold borders */
  box-shadow: 6px 6px 0 #000; /* Thick brutalist shadow */
}

.form-label {
  font-size: 1rem;
  font-weight: bold;
  color: var(--text-color);
  margin-bottom: 0rem;
}

.form-input,
.form-textarea {
  padding: 0.5rem;
  font-size: 1rem;
  font-family: "Inter", sans-serif;
  color: var(--text-color);
  border: 2px solid #000;
  border-radius: var(--border-radius);
  box-shadow: 2px 2px 0 #000;
  background-color: var(--surface-section);
}

.form-input:focus,
.form-textarea:focus {
  outline: none;
}

.form-button {
  font-size: 1rem;
  font-weight: bold;
  color: var(--primary-color-text);
  background-color: #4f92ff;
  border: 3px solid #000;
  box-shadow: 3px 3px 0 #000;
  padding: 0.75rem;
  margin-top: 1rem;
  cursor: pointer;
  transition: transform 0.2s ease-in-out;
}

.form-button:hover {
  transform: translate(-3px, -3px); /* Brutalist hover effect */
  background-color: #2d78f2;
}

.form-button:active {
  transform: translate(0, 0);
  box-shadow: none;
}

</style>
