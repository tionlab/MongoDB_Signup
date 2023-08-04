# MongoDB_Signup
Example of MongoDB server-side Signup code

## FAST START
`npm i`
`node app.js`

## Alert
- Node.js 18.XX.X require (tested on 18.16.0.)

## How to Set in Client-Side
```
const response = await fetch('[Server Link]', {
        method: 'POST',
        headers: {
          'Content-Type': 'application/json',
        },
        body: JSON.stringify({ email, password }),
      });

      const data = await response.json();
      if (response.ok) {
        Alert.alert('Success', data.message);
      } else {
        Alert.alert('Errorr', data.message);
      }
    } catch (error) {
      console.error('SignUP Error:', error);
    }```
