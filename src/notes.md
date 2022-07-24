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

MUNTER
<p>
                        “The major issue is not jobs but affordable housing and property valuations,” Munter stated in a news release. “The next Congress Member needs to support
                         the much-discussed I-35 rebuild in Duluth to reduce its size by half, giving more Lake access and new housing potential with State and Federal funding. 
                         The Department of Ag&#39;s no-money-down mortgages need to be promoted for small towns, cities, and rural areas. HUD, the State, and non-profits need to be 
                         worked with for more affordable housing.”
                    </p>
                    <p>
                        Munter is a graduate of Duluth East High School, University of Minnesota-Duluth, and in 1988 from the University of Dubuque Theological Seminary with a master 
                        of divinity degree. He is a retiree from Delta Airlines in Chisholm with a union pension and lives on a small ancestral hobby farm with his family in Warba near 
                        Grand Rapids.
                    </p>
                    <p>
                        “I am opposing Jen Schultz because she thinks copper-nickel mining can be ecological. It can&#39;t. Trading 20 years of jobs for more than 500 years of pollution is 
                        a crazy idea,” Munter stated.
                    </p>
                    <p>
                        Munter described incumbent GOP Rep. Pete Stauber as “a Libertarian who hates all government — even good government like reasonable gun regulation, flying in 
                        sorely needed baby formula, and prohibitions against oil price gouging.”
                    </p>
                    <p>
                        Munter said Stauber has promoted low-cost drugs, a cap on insulin, broadband, infrastructure and support for veterans and then voted against all of those 
                        issues continually.
                    </p>
                    <p>
                        “Most egregiously, Stauber voted against the economic interests of the 8th District in the Infrastructure bill and the financing coming in for our 29 airports, 
                        six mines, Duluth&#39;s &#39;Can-of-Worms&#39; project, clean-up of the St. Louis River, and putting an extra lock at the Soo Locks to prevent an economic 
                        disaster if it the big lock goes down and backs up our ore and grain,” Munter stated.
                    </p>
                    <p>
                        In addition, Munter characterized the national Republican platform as raising taxes on the bottom 60% of tax filers and sunset Social Security, Medicare, and 
                        Medicaid in five years.

                        “This is insane. See Rick Scott&#39;s 11 Point Program, the small print of bullet points 5 and 6. Stauber needs to disown this agenda,” according to the release.

                        Munter criticized Stauber for signing the amicus brief in the 2020 Texas v. Pennsylvania lawsuit thrown out by the Supreme Court. The suit sought to withhold 
                        the certified presidential vote count of four states, alleging those states violated the U.S. Constitution by changing election procedures through 
                        non-legislative means.

                        The suit “would have deleted the votes of four states allowing Republican state legislatures the ability to over-ride the vote of the people for spurious 
                        reasons,” Munter stated. “This is an existential threat for 2024 with Republican state legislature&#39;s side-lining the role of governors, secretaries of state, 
                        and election commissions in swing states in order to appoint their own Presidential Electors. Electing politicians who support this electoral theft cannot be 
                        tolerated.”
                    </p>

                <div class="flex flex-row contact-info justify-evenly">
                    <h5>Highschool</h5>
                    <h5>Duluth East</h5>
                </div>
                <div class="flex flex-row contact-info justify-evenly">
                    <h5>Bachelors</h5>
                    <h5>University of Minnesota Duluth</h5>
                </div>
                <div class="flex flex-row contact-info justify-evenly">
                    <h5>Masters</h5>
                    <h5>University of Dubuque Theological Seminary</h5>
                </div>

================ GET SCREEN SIZE ==================
var win = window,
    doc = document,
    docElem = doc.documentElement,
    body = doc.getElementsByTagName('body')[0],
    width = win.innerWidth || docElem.clientWidth || body.clientWidth,
    height = win.innerHeight|| docElem.clientHeight|| body.clientHeight;
alert(height + ' × ' + width);
console.log(height + ' × ' + width);

            <!-- ACCORDIAN -->
            <div class="container mx-16 bg-white border border-gray-200 rounded-md">
                <ul class="shadow-box">
                    <li class="relative border-b border-gray-200" x-data="{selected:null}">
                        <button type="button" class="w-full px-8 py-6 text-left" @click="selected !== 1 ? selected = 1 : selected = null">
                            <div class="flex items-center justify-between">
                                <span>
                                    Healthcare
                                </span>
                                <svg x-show="!selected == 1" class="fill-current" viewBox="0 0 24 24" width="24" height="24"> <!-- MINUS -->
                                    <path class="heroicon-ui" d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm1-9h2a1 1 0 010 2h-2v2a1 1 0 01-2 0v-2H9a1 1 0 010-2h2V9a1 1 0 012 0v2z" />
                                </svg>
                                <svg x-show="selected == 1" class="fill-current" viewBox="0 0 24 24" width="24" height="24"> <!-- PLUS -->
                                    <path class="heroicon-ui" d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm4-8a1 1 0 01-1 1H9a1 1 0 010-2h6a1 1 0 011 1z" />
                                </svg>
                            </div>
                        </button>
                        <div class="relative overflow-hidden transition-all duration-400 max-h-0" x-ref="container1" x-bind:style="selected == 1 && 3 ? 'max-height: ' + 1000 + 'px' : ''">
                            <div class="p-6">
                                <p>
                                    The rising cost of health care is one of the most important and urgent issues facing Minnesotans. Like many in our district, I am in favor of a single-payer system – what some call Medicare for All – that would dramatically cut down on costs associated with health insurance premiums and guarantee coverage for all Americans, regardless of income level.
                                    We are proud that Minnesota offers the lowest premiums in the country on MNsure, our state health insurance exchange. Another great program is MinnesotaCare, which provides health care coverage for people with low incomes. MinnesotaCare was created with bipartisan support and has been successful for more than 30 years. This is a public option that could be expanded to more Minnesotans and used as a template to move us forward at the federal level so everyone can access affordable, quality healthcare.
                                    It is easy to get lost in the details and in politics, but I never lose sight of the fact that, in the end, this is about real people facing some of the hardest and most terrifying experiences of their lives. Families should not have to worry that health care costs will ruin their finances in the wealthiest country in the world. Quality health care should be a right for all Americans.
                                </p>
                            </div>

                            <button type="button" class="w-full px-8 py-6 text-left" @click="selected !== 3 ? selected = 3 : selected = null">
                                <div class="flex items-center justify-between">
                                    <span>
                                        Economy
                                    </span>
                                    <svg x-show="!selected == 1" class="fill-current" viewBox="0 0 24 24" width="24" height="24"> <!-- MINUS -->
                                        <path class="heroicon-ui" d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm1-9h2a1 1 0 010 2h-2v2a1 1 0 01-2 0v-2H9a1 1 0 010-2h2V9a1 1 0 012 0v2z" />
                                    </svg>
                                    <svg x-show="selected == 1" class="fill-current" viewBox="0 0 24 24" width="24" height="24"> <!-- PLUS -->
                                        <path class="heroicon-ui" d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm4-8a1 1 0 01-1 1H9a1 1 0 010-2h6a1 1 0 011 1z" />
                                    </svg>
                                </div>
                            </button>
                            <div class="relative overflow-hidden transition-all duration-400 max-h-0" x-ref="container1" x-bind:style="selected == 3 && 1 ? 'max-height: ' + 1000 + 'px' : ''">
                                <div class="p-6">
                                    <p>
                                        I support paid sick and safe time, paid family leave, an increase of the working family tax credit, and extending the child tax credit that Congress recently allowed to expire because when working families do well, our economy and our communities do well.
                                    </p>
                                </div>
                            </div>
    
                        </div>

                        <button type="button" class="w-full px-8 py-6 text-left border-t border-gray-400" @click="selected !== 2 ? selected = 2 : selected = null">
                            <div class="flex items-center justify-between">
                                <span>
                                    Issues
                                </span>
                                <span class="ico-plus"></span>
                            </div>
                        </button>
                        <div class="relative overflow-hidden transition-all duration-400 max-h-0" x-ref="container1" x-bind:style="selected == 2 ? 'max-height: ' + $refs.container1.scrollHeight + 'px' : ''">
                            <div class="p-6">
                                <p>Infrastructure</p>
                                <p>Economy</p>
                            </div>
                        </div>
                    </li>                                
                </ul>
            </div>
            <!-- END ACCORDIAN-->
