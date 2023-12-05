---
layout: landing
permalink: /contacta/
---
<!-- Modified form HTML with Tailwind CSS classes -->

<form
  action="https://formspree.io/f/xoqogqbn"
  method="POST"
  class="max-w-lg mx-auto py-10 px-8 bg-white shadow-md rounded-lg"
>
  <div class="mb-6">
    <label class="block mb-2 text-sm font-medium text-gray-700">
      Tu email:
    </label>
    <input
      type="email"  
      name="email"
      class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
      placeholder="you@example.com"
      required
    >
  </div>
  
  <div class="mb-6">
    <label class="block mb-2 text-sm font-medium text-gray-700">
      Tu mensaje:
    </label>
    <textarea
      name="message"
      class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
      rows="4"
      placeholder="Your message..."
      required
    ></textarea>
  </div>

  <button
    type="submit"
    class="text-white bg-blue-600 hover:bg-blue-700 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center"
  >
    Enviar
  </button>
</form>