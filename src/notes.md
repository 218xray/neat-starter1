{% if location.items %}
    <ul class="absolute hidden pt-1 text-gray-700 dropdown-content">
    {% for item in location.items %}
    <li><a class="inline-block px-3 py-1 text-gray-500 no-underline transition bg-white border text-ml hover:text-indigo-500 min-w-32" href="{{ item.url }}">{{ item.text }}</a></li>
    {% endfor %}
    </ul>
{% endif %}


<li><a class="inline-block transition submenu text-ml" href="/county">County</a></li>
<li><a class="inline-block transition submenu text-ml" href="/state">State</a></li>  


ACCORDIAN
            <div class="container flex endorsements"> <!-- ENDORSEMENTS -->
                <div class="max-w-xl mx-auto bg-white border border-gray-200">
                    <ul class="shadow-box">
                        <li class="relative border-b border-gray-200" x-data="{selected:null}">
                            <button type="button" class="w-full px-8 py-6 text-left" @click="selected !== 1 ? selected = 1 : selected = null">
                                <div class="flex items-center justify-between">
                                    <span>
                                        Endorsements
                                    </span>
                                    <span class="ico-plus"></span>
                                </div>
                            </button>
                            <div class="relative overflow-hidden transition-all duration-700 max-h-0" x-ref="container1" x-bind:style="selected == 1 ? 'max-height: ' + $refs.container1.scrollHeight + 'px' : ''">
                                <div class="p-6">
                                    {% for item in teresetomanek.items %}
                                    <p>{{ item.name }}</p>
                                    {% endfor %}
                                </div>
                            </div>
                        </li>                                
                        <li class="relative border-b border-gray-200" x-data="{selected:null}">
                            <button type="button" class="w-full px-8 py-6 text-left" @click="selected !== 2 ? selected = 2 : selected = null">
                                <div class="flex items-center justify-between">
                                    <span>
                                        I'd like to run automated tests with reCAPTCHA. What should I do?					</span>
                                    <span class="ico-plus"></span>
                                </div>
                            </button>
                            <div class="relative overflow-hidden transition-all duration-700 max-h-0" x-ref="container2" x-bind:style="selected == 2 ? 'max-height: ' + $refs.container2.scrollHeight + 'px' : ''">
                                <div class="p-6">
                                    <p>For reCAPTCHA v3, create a separate key for testing environments. Scores may not be accurate as reCAPTCHA v3 relies on seeing real traffic.</p>
                                    <p>For reCAPTCHA v2, use the following test keys. You will always get No CAPTCHA and all verification requests will pass.</p>
                                </div>
                            </div>
                        </li>
                        <li class="relative border-b border-gray-200" x-data="{selected:null}">
                            <button type="button" class="w-full px-8 py-6 text-left" @click="selected !== 3 ? selected = 3 : selected = null">
                                <div class="flex items-center justify-between">
                                    <span>
                                        Can I run reCAPTCHA v2 and v3 on the same page?					</span>
                                    <span class="ico-plus"></span>
                                </div>
                            </button>
                            <div class="relative overflow-hidden transition-all duration-700 max-h-0" x-ref="container3" x-bind:style="selected == 3 ? 'max-height: ' + $refs.container3.scrollHeight + 'px' : ''">
                                <div class="p-6">
                                    <p>To do this, load the v3 site key as documented, and then explicitly render v2 using grecaptcha.render.</p>
                                    <p>You are allowed to hide the badge as long as you include the reCAPTCHA branding visibly in the user flow. Please include the following text:</p>
                                    <p>Yes, please use "www.recaptcha.net" in your code in circumstances when "www.google.com" is not accessible.</p>
                                    <ul>
                                    <li>First, replace &lt;script src="https://www.google.com/recaptcha/api.js" async defer&gt;&lt;/script&gt; with &lt;script src="https://www.recaptcha.net/recaptcha/api.js" async defer&gt;&lt;/script&gt;</li>
                                    <li>After that, apply the same to everywhere else that uses "www.google.com/recaptcha/" on your site.</li>
                                    </ul>
                                    <p>After that, apply the same to everywhere else that uses "www.google.com/recaptcha/" on your site.</p>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
