# VSCode-ESLint-setup-in-React-Native

npm i -g eslint<br/>
npm i -g prettier

eslint --init

√ How would you like to use ESLint? · problems<br/>
√ What type of modules does your project use? · esm<br/>
√ Which framework does your project use? · react<br/>
√ Does your project use TypeScript? · No / Yes<br/>
√ Where does your code run? · browser<br/>
√ What format do you want your config file to be in? · JavaScript

Update .eslintrc.js
```javascript
module.exports = {
   extends: 'airbnb',
   rules: {
      'arrow-body-style': 'warn',
      'react-native/no-unused-styles': 2,
      'react-native/split-platform-components': 0,
      'react-native/no-inline-styles': 0,
      'react-native/no-color-literals': 0,
      semi: [2, 'never'],
      'class-methods-use-this': 0,
      'react/jsx-filename-extension': [
         1,
         {
            extensions: ['.js', '.jsx'],
         },
      ],
      'react/prefer-stateless-function': [
         0,
         {
            ignorePureComponents: 1,
         },
      ],
      'react/forbid-prop-types': 0,
      'no-underscore-dangle': 0,
      'no-restricted-properties': 0,
      'no-plusplus': 0,
      'no-alert': 0,
      'max-len': 0,
      'global-require': 0,
      'react/jsx-no-bind': 0,
      'react/prefer-es6-class': 0,
      'react/react-in-jsx-scope': 0,
      'space-before-function-paren': 0,
      'linebreak-style': 0,
      'react/jsx-quotes': 0,
      'react/no-array-index-key': 0,
      'react/jsx-boolean-value': 0,
      'no-nested-ternary': 0,
      'func-names': 0,
      'no-bitwise': 0,
      'no-await-in-loop': 0,
      'jsx-quotes': [2, 'prefer-double'],
      eqeqeq: 0,
      'no-return-await': 0,
      camelcase: 0,
   },
}
