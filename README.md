Responsive React Login form built with Bootstrap 5. Collection of examples for signup forms, full page login templates, login modals & many other sign in designs.

Check out [React Login Form Documentation](https://mdbootstrap.com/docs/b5/react/extended/login-form/) for detailed instructions & even more examples.

## Basic example 
![React Login Form Basic Example](https://user-images.githubusercontent.com/108793661/179740642-436b2543-7e99-4ae6-a3da-89371056d2f9.png)
```js
import React from 'react';
import {
  MDBContainer,
  MDBInput,
  MDBCheckbox,
  MDBBtn,
  MDBIcon
}
from 'mdb-react-ui-kit';

function App() {
  return (
    <MDBContainer className="p-3 my-5 d-flex flex-column w-50">

      <MDBInput wrapperClass='mb-4' label='Email address' id='form1' type='email'/>
      <MDBInput wrapperClass='mb-4' label='Password' id='form2' type='password'/>

      <div className="d-flex justify-content-between mx-3 mb-4">
        <MDBCheckbox name='flexCheck' value='' id='flexCheckDefault' label='Remember me' />
        <a href="!#">Forgot password?</a>
      </div>

      <MDBBtn className="mb-4">Sign in</MDBBtn>

      <div className="text-center">
        <p>Not a member? <a href="#!">Register</a></p>
        <p>or sign up with:</p>

        <div className='d-flex justify-content-between mx-auto' style={{width: '40%'}}>
          <MDBBtn tag='a' color='none' className='m-1' style={{ color: '#1266f1' }}>
            <MDBIcon fab icon='facebook-f' size="sm"/>
          </MDBBtn>

          <MDBBtn tag='a' color='none' className='m-1' style={{ color: '#1266f1' }}>
            <MDBIcon fab icon='twitter' size="sm"/>
          </MDBBtn>

          <MDBBtn tag='a' color='none' className='m-1' style={{ color: '#1266f1' }}>
            <MDBIcon fab icon='google' size="sm"/>
          </MDBBtn>

          <MDBBtn tag='a' color='none' className='m-1' style={{ color: '#1266f1' }}>
            <MDBIcon fab icon='github' size="sm"/>
          </MDBBtn>

        </div>
      </div>

    </MDBContainer>
  );
}

export default App;
```

## How to use?

1. Download MDB 5 - free REACT UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)

## More examples
### Login - register:
[![React Login Form #1](https://user-images.githubusercontent.com/108793661/179741257-e1721924-fd14-491e-8cec-58e6a2d15010.png)](https://mdbootstrap.com/docs/b5/react/extended/login-form/#section-login-register-example)
### Login - register:
[![React Login Form #2](https://user-images.githubusercontent.com/108793661/179741423-aed783c4-7978-459c-be7e-20ff6032ebda.png)](https://mdbootstrap.com/docs/b5/react/extended/login-form/#section-login-page-example)
### Login Template:
[![React Login Form #3](https://user-images.githubusercontent.com/108793661/179741559-54f89d57-d4fa-49b2-9250-f5efe7f86648.png)](https://mdbootstrap.com/docs/b5/react/extended/login-form/#section-login-template-example)
### Sign in form:
[![React Login Form #4](https://user-images.githubusercontent.com/108793661/179741654-f6c7d0e3-1af9-45e3-8037-7afc1b836bb7.png)](https://mdbootstrap.com/docs/b5/react/extended/login-form/#section-sign-in-form-example)

You can find other examples [here](https://mdbootstrap.com/docs/b5/react/extended/login-form/).

<hr>

## More extended React documentation
<ul>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/code/">React Bootstrap Code</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/gallery/">React Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/hamburger-menu/">React Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/jumbotron/">React Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/maps/">React Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/mega-menu//">React Bootstrap Mega Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/media-object/">React Bootstrap Media object</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/multiselect/">React Bootstrap Multiselect</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/masonry/">React Bootstrap Masonry</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/contact/">React Bootstrap Contact form</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/gradients/">React Bootstrap Gradients</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/pagination/">React Bootstrap Pagination</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/panels/">React Bootstrap Panels</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/social-media/">React Bootstrap Social Media icons & buttons</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/search/">React Bootstrap Search</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/table-sort/">React Bootstrap Table sort</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/table-responsive/">React Bootstrap Table responsive</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/table-scroll/">React Bootstrap Table scroll</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/table-search/">React Bootstrap Table search</a></li>
<li><a href="https://mdbootstrap.com/docs/b5/react/extended/textarea/">React Bootstrap Textarea</a></li>
</ul>
