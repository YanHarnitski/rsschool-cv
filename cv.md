# Yan Harnitski

**Contacts**
E-mail: yanharnitski@gmail.com
Phone: +48 519 758 149
LinkedIn: https://www.linkedin.com/in/yan-harnitski/

**Skills**
Programming languages: HTML, CSS, Javascript
Tools: Google Analytics 4, Universal Analytics, Google Ads, Google Tag Manager, Google Merchant Center, Google Sheets, Salesforce
Version control: Git

**Code example**

Split array to odd and even

```function pickIt(arr) {
  let odd = [],
    even = [];
  //coding here
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] % 2 === 0) {
      even.push(arr[i]);
    } else {
      odd.push(arr[i]);
    }
  }

  return [odd, even];
}
```
