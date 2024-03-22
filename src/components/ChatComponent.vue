<template>
  <div class="q-pa-md row justify-center">
    <div style="width: 100%; max-width: 400px">
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Welcome!, I am Agustín Danel Vissani, an enthusiastic systems analyst. Pleased to meet you.',
        ]"
        stamp="17 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="['How are you today?']"
        size="6"
        stamp="14 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'I\'m fine thanks.',
          ' Excited for this opportunity and ready to talk about my experience and how I can contribute to the team.',
        ]"
        stamp="14 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="[
          'I\'m glad to hear that!',
          ' Before we begin, would you mind telling me a little about yourself?',
        ]"
        size="6"
        stamp="13 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Of course.',
          'I am Agustín Danel Vissani, an enthusiastic systems analyst with a great passion for technology and problem solving.',
          'I have been immersed in the world of computing since an early age, which led me to obtain my secondary degree in \'PERSONAL AND PROFESSIONAL COMPUTER TECHNICIAN\.',
          'Later I continued studying and received my degree in \'SYSTEMS ANALYST\'.',
        ]"
        stamp="12 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="[
          'Sounds awesome, Agustín. ',
          'Can you tell me a little more about your previous experience?',
        ]"
        size="6"
        stamp="11 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Of course.',
          'Recently, as a Frontend developer in a personal project as a freelancer, I had the responsibility of developing an application using React. This involved creating a modular, component-based structure, integrating APIs with dynamic communication between the application and the server through Axios, and designing the interface using libraries such as Tailwind CSS and DaisyUI.',
        ]"
        stamp="10 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="[
          'Interesting. And what has your experience been like in previous roles? ',
        ]"
        size="6"
        stamp="9 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="[
          'Previously, at Connectis S.A., I worked as a QA Tester on a project for Telefónica in Uruguay. My responsibility included performing regression, usability, compatibility and functionality testing, following the Agile methodology.',
          'Additionally, at MAS Tecnología, I played the role of warehouse assistant, where I acquired practical skills in PC assembly and warehouse operations at a technology wholesaler.',
        ]"
        stamp="9 minutes ago"
        sent
        bg-color="amber-7"
      />
      <q-chat-message
        name="RRHH"
        avatar="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
        :text="['Excellent! Could you add IT SKILLS?']"
        size="6"
        stamp="9 minutes ago"
        text-color="white"
        bg-color="primary"
      />
      <q-chat-message
        name="Agustín Vissani"
        avatar="https://lh3.googleusercontent.com/a/ACg8ocKkrIKOgNGiFBxRMM4ps8hS7DYNXyCdxK6J6jH0ROAocg=s288-c-no"
        :text="['Sure, I\'ll leave them here']"
        stamp="9 minutes ago"
        sent
        bg-color="amber-7"
      />
    </div>
  </div>
  <div class="text-h6 text-white q-mx-auto" style="max-width: 600px">
    <div class="text-h6 text-white">
      Test Automation:
      <q-avatar class="q-mr-xs"  @mouseover="showName = true"
        @mouseout="showName = false">
        <span v-if="showName">Playwright</span>
        <img
          alt="Playwright"
          src="data:image/png;base64,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"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Appium"
          src="https://miro.medium.com/v2/resize:fit:1008/1*3D873F7NqtSUbZso8eCfNQ.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Cypress"
          src="https://static-00.iconduck.com/assets.00/cypress-icon-2048x2048-swmlmjca.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Selenium"
          src="data:image/png;base64,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"
        />
      </q-avatar>
    </div>
    <div class="text-h6 text-white">
      Programming Languages:
      <q-avatar class="q-mr-xs">
        <img
          alt="JAVA"
          src="https://st3.depositphotos.com/13803186/19300/v/450/depositphotos_193009322-stock-illustration-java-source-trademark-logo-design.jpg"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="PHP"
          src="https://static-00.iconduck.com/assets.00/php-icon-256x256-oq5bc0bt.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="JavaScript"
          src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Selenium"
          src="data:image/png;base64,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"
        />
      </q-avatar>
    </div>
    <div class="text-h6 text-white">
        Databases:
      <q-avatar class="q-mr-xs">
        <img
          alt="Sql Server"
          src="https://i.pinimg.com/originals/3e/55/df/3e55dfb0980956b42cac768b740cdad6.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="MySQL"
          src="data:image/png;base64,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"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="MongoDB"
          src="https://banner2.cleanpng.com/20180702/bgt/kisspng-mongodb-database-nosql-postgresql-mongo-5b39f9e3445fa6.5652746415305261792801.jpg"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Firebase"
          src="https://ih1.redbubble.net/image.489553250.2202/flat,750x,075,f-pad,750x1000,f8f8f8.u1.jpg"
        />
      </q-avatar>
    </div>
    <div class="text-h6 text-white">
        Web design and development:
      <q-avatar class="q-mr-xs">
        <img
          alt="Laravel"
          src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAT4AAACfCAMAAABX0UX9AAABEVBMVEX4+PgBEhwAAAD////4///4+Pn4+Pb/FQD57vD6EQAAAAj//fsDERymrauAgoX7+/sBEhr5jo0AAhD6+v9DUFP5JRf3YFh4e36Fi5CPlZv1///GzNH2xsH2sKnT2d0ACxegpafzzcvzzsb4h4LHx8b4bGJYY2v4p6b/JBL6Nif3kov2qaLq6+zd5OZYY2wAABX34uP319f4Z2X3npazur31Qz326OH2cGr1ra74PzX2TEb41Nf2U0L0dXL1vLb3vML4wbb2hYfzRCz1gnf5cnL0Jwr1t635joL1Pjr3lZD4KyD/Hxn1YF33XFDzfG73SUg4QEYaJi8kLDQ/REoMHSJpcHVPUlcpMzdoaHDk4+E5PkXPJAyOAAAOmklEQVR4nO1dC1vT2BZNcx5p2sIpLQFJS8NLSKFci7ydkbmjo46tekUoXP3/P+TuvU+apmlBVEbJzVnfzHwlOUmT1bWf5yRjWQYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgY/G1LxX30JGYbwu02ufvVVZBSCy23XPVzjSv7qS8kgFF/uhaETuo+7xoK/FYqvHgJ1281Dp+/OSUPgN4EfHbuh+67LlTqBD95r4wLvDi73gbPTJqtbUvjyjRs6z/a4+NWXlQ3U+UnPCcMdXseQIaTFuwtA4IcjLgyDX4Piv/0O0luXXFoyCrmcN9uwbf9WF2jMG6CKz0FpC3scuEuIjaudMHTbZzfyp9QfR9wkODIMvcMmmCkoTySNlR+th56zM50/iNOnjvvWBOii2/Pay5yD9uSYmHj3sec5c1MIAud49BgkGzq9s7xbMNAXYtDloi5H2hO8uO70Q8+dRh+Xc0DeYXMdA/RavgksuuHZc7fvLBz5Uo5CB3i+0Pv3whT1cf7ac9xXJ1zw7ntQ4POi/7Ov+QGh6DpruuD4E2Iv0Sd482+Iu3MWfzdBn/QTY2FgG2qUfZXfFBHpq0tQVOi+AhdoYcx4CgQdQ9bH0+oT7OjYoeLE0mGaK8y32/l1gUDfal1KbLaAP1vjXKzrDxCGU/RJLoAs50UTEhZh6Sgt/KPnDph+XrsMEX1S8e4xGOLxcs91X21xheyk6ONnPddxd+ocqYuTHMH3wAW6L4u5TAK18aIpSt48xHTE3S4qRWnMOH18x/HCN0WIMDAWPV+0XUCNcuq5PZVHB5igT3K+HIYLXX8YgVP0QRrd/wsDNA5OnEKxnbbnuT/5wh8GtPFiLgz2KLnnvOaj0neCPlDntsWxrRCDwm/oem6ejRc/gqiAvuUEYSn6nMdnnosBWsYZNoSO9xB7X74Oc0vfqood2dfo88Ubt+8erg4TPSWp9PiNN5080yfuSB/kgkfvoNQ4LmK3BYqTV47bO+GqnmP61urxnX+dPilZ82/wdW8tH7suEKeFj/7P0GfdgT5MaEB0bhj2lo9Rhl10hLmmb/Vb1EdtLV++BN1BcbLKdbaXZ/q+0XgpzPDuQt87Kde1z5TS0Ie4A33Dv3acNo/zlzyr75uMN06ptwx91o/SF2sxx/Stqe8xXqTPMvSB+uSd6fPjuThjvIRvCx3+aKShD3Fn+rh8Hx6OZsaBvl68iIPzbTffDSuNG+nj9X2oNLzR0jVSn/aEkjfbsC+X0x13Up/CNS99982reD4pQR/vvnNpaulnX/pDwB3o0xO67oeib+HStd9XcV5NR15L+NSy+s9aTucqv04fL667nvP7nsK5t+4CzifhKkqqOhRfhtrXW2a5lJ71dd/nq53QdXpnDHuqOH1EXaq3iqH6ePMU2NyGsJLLeSLrq+p7u/oC2ZI8ml+TgvOt0HV7zR3ntPjYxYXk/vjSrFzh9rS534sWHGCfT5L+pOTFl07faXu4Dv9vdIRCyLzyd0vRxsWh59GCA9yfyIoVtqt6nhd6W4ynZi1zhhuNl6tlL3Q8yFMmlSX8vTaw92cR6g50iPnl74bQIfgqzmhsW2rSrwlczwHSazPs0wspc2q4iKnqk3r5KEWFiSMUPrrlHH4IgT7LyqvTizCFPsGtbVDe6Rq39GqWJHB1JGR6W3wZ876ffrkPDZP0+fRsW0hOL82PHK6kZD6lzekF0bnDhO97vfcMCHoj65ZMKw/K27+cEBfzQfai6ZsYkjOk1eedgtN7151il/S8ap9WkcPOulEfIp02A140oUKbCKfcP/Ecx12WPu1RRn2IaIlQBO71e+0jVk6sftRQvIlOb074lt5j1EdIGe9q2/WoxB0bhJme23eedkdTRRF9lqEvETogL9nqh2HvhCe2gdN7Q8+r4oqM4WZl6EOk6KPniWj1ij9svnP1GvKYcIePPf5ijJcwbrwIwY8WwM09PcIGslR8DReMz1mpZ4dM6CBM0hcXvHNFLukZGXR66eOM+ghp49XAt2rgKmaBD8ucrvLJroracY36iL7mtNqVHjNyAd7J1Pe6+PuuUR89kHrDY82QrISeuz71gUle/MsNTeQFIpbD0AGFTXtul7935vxJfQn9IOCLNZV720UrXXdome0kEXzB2Z7crPgZPkG9n9vJyXFIHxMV5/hoYqYb6WOp8k3xvWcQTl4WucjlqowpEDhfG7pvRcrN+ZPq48UPTt9d2OP5nZucAq62+u7Emx1QfSo5B6n8LTcM22e+nOgp5By6Vnu2lySQ1JcgTz/8t29eUDcF4NTeu/hmh7FVBtsqTk1YF13k8yPfyG4qIKTSq5fiNzvoyEv0CR2gn+35eZ9buwWK3qTWHr6AMw4dss5podAftCLj117jQ4bgxefg3vCVVtYwdODT9qun9EawMr6oKfeZ8m3AvA5SE8zrRKQ+3o3yQuwb5EN8CvGdh/LXWFXslDmpj8tth162ROtZ7uO6fvQc/zw6Gt95pVy9xT5Vky04+/wkdBxvmZVxx48qT1/Vgzd+tmgjZtl3Hi98fJWpc/x7+JjmzPFVh/dgtOwRXdZK+cdP9Y+CzZYKhYL96HvpIxf4wg29Xui5T7u+kOI+nB5bsivVqj3z/08ftqtOeq4HJsz5fcVaoK9aLeSDPlxdun26xbl1b6kK0leo5IU+yJt5vX4vF6SBxlvIhvoqlXug756XzJP68kTf/SJD6rsX471nZEh9D5S+gqHvu5Eh+m7zfVh4JkLC1PCQ3HhDnXqHw8aPy5Dx3kgfY/XdVmuXMUV/AIhKlsKQX8VYp9VqdRjTfzA6UI9JraC84bgRhdkPHUzMXFHhaS+2mOoMFgFLMIytLI5h0NJLcFlr9pKGf1ypKzajdyk+Sx86yTOrDTpwRunjGoMaHXf+aDemOUPqm0qfYis1uwZ1J8C2B/WOXSqV7Aukb9Ou1Uol/Af+hY0bJM7dTbsUwC1XC4F92WCLMKhmNxSbtWGcvZK0TTZP2xp0XOsLHFfQx9kDEV1HhtQ3zXiVf2XjTUWwP+6iK6/Nw7DyZg3utVoFauG/sA9pYAfENW0oVAP74FEJBsEutQs8VIPrxDoD3ARkfUKpsUd2rZr4nlJLD8yQ+qbQpzrXePsggEKFGCnNB0P6GNJXARTovitIH1sBkmgk/oM3Pk+yxV0XqEm7NeHXVvBcA5vOUQLbreGnwG6xxJgs0DfFePlFicgBp1TSN0ZSTKgvRtXekGzDRqqrFRgO41GEAdIYMQujS4mGoroMKjC0IwRor4I/QDBYWno0r7/Hps5thhKXSfrw4qt4K5uNTufzwebQjof0VVAZMTbKnSBA+uzq0m6n01q5RMIKSBHQJzo2CjGIY6/aQHOubTKhGnYVRGsv6fC8e0UO4opZ2aZPdej+gycNzC4UxMYgGNGHxgtHHLSG6LDFEpo5On5M4Fh9EcRYjewaDLSEGj0YWm90fKMs1Cey60aUsCiIN7gHQ1GGjHfC90G0LIBvQzekb4xR4EgYLzmzGB2bfOCAWfohfJwBqMb0gdpAfVpUCPptggBM98Am7cXpnlLXwfA3ynLoqARkOSzufcKdjtT3r4i+eOcK7gzOE8GVfQyGUQX++ASmXbF3VWJ06VEZ8pcn4CVriTah/hocmSH1pY0XXBLcenCuEq1jzce4+uJ9V+gMge3EWQ90TGhEYQCpWNL72Rf0k3ZLogyrhdqAjWTMGIYcjMkZUl+aPq0P2CTT20a+r5qkD+IMEDJWWFi1EX1g3JjnndNXYLioVmoXTKJRV0CGjY0RGhdAX2nAsqw+iAQUG3ii0od7HVNfgj5ipwpZ8Nhpr2oxffjHML2Gk9cKegqNckUgy06CNH6RKfWlfR+FyrFElyqFG+lrIX14z1bqHEP61AFyAWYKnwUYOtAnpIiyo0ngL5GhxOVG+hK+L0EfS/k+3HU7fZYgnjAh1k4RzZMYqtxCX3aNl375g7K82XgLY8aLVcb5GH3l+YTxUiYUhYSrJ4VhmbxC9NmTuGYyQ8Y7PXSUZpP0aWOanrjwUhWntHeTxi4p0RnSB/aNqvrCqFsQ+Um2oTndnYTMkvrSxkuJSyG4rCdXen+6NXFB+laSv8CMTYXd0HjZR+0vI1EtMfAL6jP9SouJxAVzF914zpD6JtJmqOkLdJMxfVqQNyUuM1RHVEW8DlzUz4NKQn2xoNklFnPgBPGtOOyavib50IfqNKLsMDvq08Y7EgA24bTpDTllLSqCp0deSwnaW9pU0c0q9l9d5MX0RZXaZQMzwNomQ7cgtEOAMDI6k/8FRByl2llRH5lQ5/MQu0IXsbjEhCGrHMJlomUwQV9M90VHtww6m5q96og+3TcIUJQV7B6gXxC6M2HPEmEC2/3ntYI9wOXmGUpc8E6fJAJfS0W2CoSstHZbMxd2lGBMTVxwzuxctwPt2Uar1Zi1S4U0fXXyp9Q1DKrD4lh/TdW+alHD6vMs/Ur2tciU8VbGsy+q2CP96DkcpKs2rr7xrBozZ9IrlRAlbDsH4/RZ7HLY+wdHEflUGX1Nzb4ezA6+2NT2CnRWkx3jHaevShkIn7fHOSXOpicuFrUIhuzoQiK4CsZ8X2SN0c8zDEmqHn1NUCvVIv9QakXt0qyorzAOncDVB2NTRfPoDqs3qQ9O0wgSfNfsho5II/pU1DIs1D6yUTWj1KKe44hQsT92qFORGfUtTiT9mhh28AlnELGnZEMO06FdF0RfYtToPAJOVCPrK9nXLTagQY1EfIkmjcfyQ+T9wrafoAFUAvwirktFoC8Ta5vVxkoaUedJscbiJ5r2XoKIKmgXzmyrAz0qtRoDAu7KFfrKJwNIeKLTJioR1RqdXowd11raDPB7nmzOCKb/L4SQutPY1kOnL1owkURiV1l1OnXGsAGvhusqRLz+YvJMZdmRcJBILNJI7Ob6FBMvvSrjcR1RTg6/6Usyhm99EDwXTxIZGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYZBD/A14rh0Qb5L4WAAAAAElFTkSuQmCC"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="React"
          src="https://miro.medium.com/v2/resize:fit:522/1*NJSv6DGoKTloI8d8im98zg.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="HTML"
          src="https://www.cnet.com/a/img/resize/6f59de6f421aca65461420ada94716b37c756c87/hub/2011/01/18/8d118cb0-fdc0-11e2-8c7c-d4ae52e62bcc/HTML5-wow.png?auto=webp&fit=crop&height=675&width=1200"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="CSS"
          src="https://logowik.com/content/uploads/images/123_css3.jpg"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Tailwind"
          src="data:image/png;base64,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"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Quasar"
          src="data:image/png;base64,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"
        />
      </q-avatar>
    </div>
    <div class="text-h6 text-white">
       Others :
      <q-avatar class="q-mr-xs">
        <img
          alt="Postman"
          src="data:image/png;base64,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"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="JIRA"
          src="https://visuresolutions.com/wp-content/uploads/2022/07/Logo-Jira.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Azure"
          src="https://download.logo.wine/logo/Microsoft_Azure/Microsoft_Azure-Logo.wine.png"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Figma"
          src="data:image/png;base64,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"
        />
      </q-avatar>
      <q-avatar class="q-mr-xs">
        <img
          alt="Adobe"
          src="https://logowik.com/content/uploads/images/adobe-inc-a878.logowik.com.webp"
        />
      </q-avatar>
    </div>
  </div>
</template>

<script>
export default {
  name: "ChatComponent",
  data() {
    return {
      showName: false,
    };
  },
};
</script>

<style scoped>

</style>
