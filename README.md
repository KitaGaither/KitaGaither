import React, { Component } from 'react';
import { Container, Row, Col } from 'reactstrap';
import mecircle from '../images/mecircle.png';


class Contact extends Component {
    render() {
        return(
            <div id="contact">

                {/* <h1>Contact This Game Developer</h1>
                    <div className="contact-div">
                        <h2>Lakita Gaither</h2>
                        <img 
                        src={mecircle}
                        alt="lakita gaither"
                        className="about-img"
                        />
                        <p>Hi, I'm Kita! I am a Full-Stack Web and Mobile Developer. </p>
                    </div> */}

                    <h1>Contact me on Social Media</h1>
                    <Container style={{ width: '100%', margin: 'auto' }}>
                        <Row className='landing-grid'>
                        <Col col={12}>
                            <img src={mecircle} alt='lakita gaither' className='avatar-image' />
                            <div className='banner-text'>
                            <h1>Full-Stack Web Developer</h1>
                            <hr />
                            <p>
                                JavaScript | HTML/CSS | Bootstrap | MongoDB | Express | React |
                                React Native | Node
                            </p>
                            <div className='social-links'>
                                {/* LinkedIn */}
                                <a
                                href='https://www.linkedin.com/in/lakitagaither/'
                                rel='noopener noreferrer'
                                target='_blank'
                                >
                                <i className='fa fa-linkedin-square' aria-hidden='true' />
                                </a>

                                {/* Github */}
                                <a
                                href='https://github.com/KitaGaither'
                                rel='noopener noreferrer'
                                target='_blank'
                                >
                                <i className='fa fa-github-square' aria-hidden='true' />
                                </a>

                                {/* Freecodecamp */}
                                <a
                                href='https://www.freecodecamp.org/kitagaither'
                                rel='noopener noreferrer'
                                target='_blank'
                                >
                                <i className='fa fa-free-code-camp' aria-hidden='true' />
                                </a>

                                {/* Youtube
                                <a href="http://google.com" rel="noopener noreferrer" target="_blank">
                                <i className="fa fa-youtube-square" aria-hidden="true" />
                                </a>
                                */}
                            </div>
                            </div>
                        </Col>
                    </Row>
      </Container>

            </div>
            
        );
    }
}
export default Contact;


![IMG_1172](https://user-images.githubusercontent.com/33188711/123331937-8651e980-d505-11eb-8378-af26f8c83851.GIF)


🧜🏼‍♀️  Hi, I’m Kita!
I’m currently learning Javascript, MongoDB, Express.js, React.js and Node.js. I’m looking to collaborate on Javascript and MERN projects. You can reach me here on github. Peace! ✌🏽


