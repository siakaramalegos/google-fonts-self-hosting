# Speeding Up Google Fonts

This is one of the repos I used for testing out different strategies for using Google Fonts on a website. I tested each one using webpagetest.org using the easy setting.

## Tests

### No preconnect vs preconnect

**Without preconnect**
- Code: https://jsbin.com/xacifi/2/edit?html,css,output
- Deployed website: https://output.jsbin.com/xacifi/2 
- Test results: https://www.webpagetest.org/result/181201_ZV_d2501e805704442e60427024aff7ecb7/

**With preconnect**
- Code: https://jsbin.com/kegerux/2/edit?html,output
- Deployed website: https://output.jsbin.com/kegerux/2
- Test results: https://www.webpagetest.org/result/181201_1K_47ce3f04ea4ceb6b8793f4f8046df388/

### Preconnect vs self-hosting and preloading

**With preconnect**
- Repo: https://github.com/siakaramalegos/google-fonts-preconnect 
- Deployed website: https://angry-snyder-f34116.netlify.com/
- Test results: https://www.webpagetest.org/result/181212_0B_6134652d0ad5e16e8ac00b14775bd536/ 

**Self-hosting and preloading**
- Repo: https://github.com/siakaramalegos/google-fonts-self-hosting
- Deployed website: https://elastic-snyder-7a396e.netlify.com/
- Test results: https://www.webpagetest.org/result/181212_NC_aea1f110b647708e2c63dcf0b94b526e/ 

**Self-hosting without preloading**
- Repo: same as above, but no-preload branch
- Deployed website: https://confident-wright-fbdec1.netlify.com/
- Test results: http://webpagetest.org/result/190406_S0_0a529e9ce6086cbea8e3aadc942ddbf6/ 

### Calling from HTML vs CSS

**Calling from CSS**
- Repo: https://github.com/siakaramalegos/google-fonts-css-call
- Deployed website: https://wonderful-pare-a1c5b1.netlify.com/
- Test results: http://webpagetest.org/result/190406_EP_2dc139e2f92f617a2ec5f39624d6c8ca/

**Calling from HTML**
- Repo: Same as above, but call-from-html branch
- Deployed website: https://happy-kirch-d50652.netlify.com/
- Test results: http://webpagetest.org/result/190406_R6_728f420f9a8b16fd4cd3ad925bd71018/
