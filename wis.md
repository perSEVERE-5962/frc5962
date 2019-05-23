---
title: Women in STEM Day
---

<form action="https://docs.google.com/forms/d/e/1FAIpQLSf3LKE8p3xl8G38HcA_ATfw_aOcSuyIuQDsV1E_lzKn3ddBNg/formResponse" method="POST" target="secret-frame" onsubmit="showThanks();">
    <div class="form-header">
        <h2 class="form-title">Register Today</h2>
        <p class="form-description">
            <p>Women in STEM Day is being run by FRC Team 5962, a high school robotics team in the Merrimack Valley. Join us for a day of hands-on activities in engineering and more! Any girls ages 11-18 are welcome. <b>Absolutely no experience is needed</b>, and lunch will be provided!</p>
            <p>The deets: Saturday, June 8, 10am-3pm, UMass Lowell Makerspace (Falmouth Hall 102)</p>
        </p>
    </div>
    <div class="form-content">
        <div class="form-question">
            <label class="form-question-title-container" for="emailAddress">
                <span class="form-question-title">Email address</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <div class="text-input-container">
                <input aria-label="Your email" autocomplete="email" name="emailAddress" id="emailAddress" required="" tabindex="0" type="email" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="firstName">
                <span class="form-question-title">First name</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <div class="text-input-container">
                <input aria-label="First name" autocomplete="off" name="entry.1956224798" id="firstName" required="" type="text" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="lastName">
                <span class="form-question-title">Last name</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <div class="text-input-container">
                <input aria-label="Last name" autocomplete="off" name="entry.1929112542" id="lastName" required="" type="text" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="school">
                <span class="form-question-title">School</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <span class="form-question-description">This event is for high school and middle school students. Please provide the full name of your school.</span>
            <div class="text-input-container">
                <input aria-label="School" autocomplete="off" name="entry.141995036" id="school" required="" type="text" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="age">
                <span class="form-question-title">Age</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <div class="text-input-container">
                <input aria-label="age" autocomplete="off" name="entry.29691098" id="age" required="" type="number" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="parentName">
                <span class="form-question-title">Parent name</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <div class="text-input-container">
                <input aria-label="Parent name" autocomplete="off" name="entry.1574004266" id="parentName" required="" type="text" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="parentEmail">
                <span class="form-question-title">Parent email</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <div class="text-input-container">
                <input aria-label="Parent email" autocomplete="email" name="entry.1718861784" id="parentEmail" required="" type="email" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="diet">
                <span class="form-question-title">Dietary restrictions</span>
            </label>
            <div class="text-input-container">
                <input aria-label="Dietary restrictions" autocomplete="none" name="entry.1260884242" id="diet" type="text" />
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="learn">
                <span class="form-question-title">What do you hope to learn from the event?</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <span class="form-question-description">E.g. engineering skills, to building a network, learning how to navigate STEM classes to prepare for college, anything else</span>
            <div class="text-input-container">
                <textarea aria-label="What do you hope to learn from the event?" autocomplete="none" name="entry.1065438568" id="learn" required=""></textarea>
            </div>
        </div>
        <div class="form-question">
            <label class="form-question-title-container" for="familiarity">
                <span class="form-question-title">Briefly, what's your current level of comfort/experience with STEM?</span>
                <span aria-label="Required question" class="required-asterisk">*</span>
            </label>
            <span class="form-question-description">No experience is required/expected, but this helps us make the event better for you.</span>
            <div class="text-input-container">
                <textarea aria-label="Briefly, what's your current level of comfort/experience with STEM?" autocomplete="none" name="entry.490258146" id="familiarity" required=""></textarea>
            </div>
        </div>
    </div>
    <input type="submit" id="submit-button" class="button inactive" value="Submit">
    <h3 id="thanks" style="display:none">YAY! Thanks for registering! You're all set—we'll send you an email to remind you about the event when it gets closer.</h3>
</form>

<iframe name="secret-frame" width="0" height="0" border="0" style="display: none;"></iframe>

<script>
function showThanks() {
    document.getElementById('submit-button').classList.add('inactive');
    document.getElementById('thanks').style.display = "block";
}
</script>
