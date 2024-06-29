Anna Barinova
*******************


**Contacts**
*******************
* Email: annbarinova.116@gmail.com
* Telegram: @ana_malenia
* Discord: Nan (@Anna1719)

**About me**
*******************
My goal right now is renew my knowledge in front-end development and potentially gain more understanding of the current requirements for a position of junior software developer. Even though I have previous relevant work experience, I am certain that my skills could be improved, so I appreciate any feedback and constructive criticism.


**Skills and Proficiency**
*******************
Programming languages and libraries:
* JavaScript
* HTML5
* CSS3
* React
* JQuery
* Java, C++, Python (intermediate level)

Version control:
* Git

Editors:
* VSCode
* IntelliJ IDEA


**Code examples**
*******************
A piece of code from a [project](https://github.com/Anna1719/neoflex_project) made for a study course (using React and TypeScript):
```
import style from './Contacts.module.css'
import {contactNumbers} from '../data/ContactNumbers'

export const Contacts = () => {
    return (
        <div className={style.wrapper}>
          <h3>Наши контакты</h3>
          <div className={style.contact_wrapper}>
          {contactNumbers.map((contact) => (
            <div>
                <ul>
                    <li>
                        <div className={style.name_info}>
                          {contact.organization}
                        </div>
                        <a className={style.contact} href={contact.num_contact}>
                          {contact.contact}
                        </a>
                        <div className={style.address}>
                            {contact.address}
                        </div>
                    </li> 
                </ul>
            </div>
          ))}
          </div>
        </div>
    );
};

```
