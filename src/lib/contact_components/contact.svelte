<script>
    let textToCopy = "jacksonmaddoxaudio@gmail.com";

    function copyToClipboard() {
    // Create a temporary textarea element
    const textarea = document.createElement("textarea");

    // Set the value of the textarea to the text you want to copy
    textarea.value = textToCopy;

    // Append the textarea to the document body
    document.body.appendChild(textarea);

    // Select the text inside the textarea
    textarea.select();

    // Execute the copy command
    document.execCommand("copy");

    // Remove the textarea from the document body
    document.body.removeChild(textarea);

    // Inform the user that the text has been copied
    alert("Email copied to clipboard!");
  }
</script>


<section class="min-h-screen mx-auto rounded-xl shadow-lg my-8 p-8 bg-white grid grid-cols-1 gap-5">
        <div class="flex items-center justify-center bg-white mx-auto max-w-lg p-4">
            <div class=" text-center">
                <h1 class=" text-2xl md:text-4xl font-medium uppercase">Book a Session:</h1>
                <p class="mt-3 font-thin">Email me at <button class="hover:underline" on:click={copyToClipboard}>jacksonmaddoxaudio@gmail.com</button>  or message me here:</p>
            
                <!-- Form -->
                <form action="https://api.web3forms.com/submit" class="mt-10" method="POST">
                    <input type="hidden" name="access_key" value='bjhb' />
                    <div class="grid gap-4">
                        <label for="name" class="sr-only">Your name</label>
                        <input type="text" name="name" id="name" required class="block w-full appearance-none border-b border-gray-500 bg-transparent py-2.5 md:py-2 px-0 md:px-0.5 text-sm text-gray-900 focus:border-blue-600 focus:outline-none focus:ring-0" placeholder="Your name" />
            
                        <label for="email" class="sr-only">Your email</label>
                        <input type="email" name="email" id="email" required class="block w-full appearance-none border-b border-gray-500 bg-transparent py-2.5 md:py-2 px-0 md:px-0.5 text-sm text-gray-900 focus:border-blue-600 focus:outline-none focus:ring-0" placeholder="Your email" />
            
                        <label for="message" class="sr-only">Your message</label>
                        <textarea name="message" id="message" required rows="5" class="block w-full appearance-none border-b border-gray-500 bg-transparent py-2.5 md:py-2 px-0 md:px-0.5 text-sm text-gray-900 focus:border-blue-600 focus:outline-none focus:ring-0" placeholder="Your message"></textarea>
                    </div>
            
                    <!-- Captcha -->
                    <div class="h-captcha" data-captcha="true"></div>
            
                    <!-- Honey Pot for Bots -->
                    <!-- <input type="checkbox" name="botcheck" class="hidden" style="display: none;"> -->
            
                    <!-- From Name -->
                    <input type="hidden" name="from_name" value="id-dev | inquire">
            
                    <!-- Submit button -->
                    <button type="submit" class="mt-5 w-full md:w-auto rounded-md bg-gradient-to-br from-yel_orange to-giants_orange hover:opacity-80 duration-200 px-6 py-3 md:px-8 md:py-3 text-white ">Send Message</button>
            
                    <!-- <div class="g-recaptcha" data-sitekey="6LcsMYMnAAAAAKSyZNepGYnV98pyRUpBK7dNtVCF"></div> -->
                </form>
                <script src="https://web3forms.com/client/script.js" defer> </script>
            </div>
        </div>
    </section>