<img width="1191" alt="va header" src="https://user-images.githubusercontent.com/104940944/171872105-9676d357-4a29-4427-9dfa-4f4d846f75be.png">

> A design system for Experience Cloud
* Modern U.S. federal government web standards
* [VA.gov](https://www.va.gov/) web presence
* 21st Century Integrated Digital Experience Act
* Section 508 of the Rehabilitation Act

## Start
1. Intiate design system with the following aassets: site_template, VAuswds
2. Confirm org permissions

## Build
1. Activate site
2. Create custom pages
3. Use web components

```
Sign-in form component

<form class="usa-form">
  <fieldset class="usa-fieldset">
    <legend class="usa-legend usa-legend--large">Access your account</legend>
    <label class="usa-label" for="email">Email address</label>
    <input
      class="usa-input"
      id="email"
      name="email"
      type="email"
      autocapitalize="off"
      autocorrect="off"
      required
    />
    <label class="usa-label" for="password-sign-in">Password</label>
    <input
      class="usa-input"
      id="password-sign-in"
      name="password"
      type="password"
      required
    />
    <p class="usa-form__note">
      <a
        title=""
        href=""
        class="usa-show-password"
        aria-controls=""
        data-show-text="Show password"
        data-hide-text="Hide password"
        >Show password</a
      >
    </p>
    <input class="usa-button" type="submit" value="Sign in" />
    <p>
      <a href="javascript:void()" title="Forgot password">Forgot password?</a>
    </p>
  </fieldset>
</form>
    
```


## Publish
Visit public URL to preview site


#### Example: [Compassionate Care Innovation](https://ccidev-vacommunity.cs133.force.com/ccisubmissionportal)
