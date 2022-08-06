# Thesis Report - Application of chaos theory into end-to-end encryption in communication systems

## Introduction

The thesis, what named <b><i>"Application of chaos theory into end-to-end encryption in communication systems"</i></b>, is aimed to research the application of chaos theory in cryptography. After that, chaotic cryptography is applied to end-to-end encryption to grow up the security of data in the communication. Finally, the thesis is implemented a messaging application on the android device using the researched knowledge.

The results of the thesis meet the requirements set forth: The correct encryption and decryption cryptosystem; The key exchange process is correct so during the messaging process, the message is encrypted and decrypted properly. However, the process of encryption and decryption using chaotic cryptosystems has not been optimized, it is necessary to research, develop further, and research and implement more encryption with photos, videos, or in real time such as: call, video call.

## Module
### Module 1: [Chaotic Cryptography](https://github.com/longbaby5512/chaotic-cryptography.git)

Module is implemented the chaotic cryptography with 3 blocks:

- <b>Block 1.</b> The permutation block. This block is used to permute the data to the permuted data. It is aimed to break the statistical structure of the data, create dependency between the data, and the secret key.

- <b>Block 2.</b> The substitution block. In this block, the data is replaced using the substitution box (S-Box).This technique is used to hide the statistical properties of the data and reduce the correlation between neighboring data.

- <b>Block 3.</b> The diffusion block. Plaintext selection attacks are designed to break cryptographic systems by examining how a small change in a plaintext image can affect the system's cryptographic results. An efficient diffusion phase can make cryptographic systems resistant to these types of attacks.

### Module 2: [Key exchange using Elliptic Curve Diffie-Hellman Algorithm](https://github.com/longbaby5512/ecdh-key-exchange.git)

Module is implemented the key exchange using the Elliptic Curve Diffie-Hellman Algorithm using the library of Java. In where, the ECDH (Elliptic Curve Diffie–Hellman Key Exchange) is anonymous key agreement scheme, which allows two parties, each having an elliptic-curve public–private key pair, to establish a shared secret over an insecure channel. ECDH is very similar to the classical DHKE (Diffie–Hellman Key Exchange) algorithm, but it uses ECC point multiplication instead of modular exponentiations.

### Module 3: [The server of the application](https://github.com/longbaby5512/chat-app-server.git)

The server is used to store the infomation of the user and the message. The server is implemented the chat application using NestJS framework, RESTful API, Socket.io, and PostgreSQL.

### Module 4: [The client of the application](https://github.com/longbaby5512/chat-app-android.git)

The client is android application. It is used to sign in and sign up the user, implement the chat application with the server developed in the Module 3.

## Clone the repository

To clone the repository with submodule, you can use the command:

```bash
git clone --recurse-submodules -j8 git@github.com:longbaby5512/karry-thesis.git
cd karry-thesis
```

## Language & Framework
- Module chaotic-cryptography: C/C++
- Module ecdh-key-exchange: Kotlin
- Module chat-app-server: TypeScripts with NestJS framework
- Module chat-app-android: Kotlin, C/C++

## Stay in touch
- Facebook: [Long Nguyen Van](https://www.facebook.com/longkenvy)
- Github: [Nguyễn Văn Long](https://github.com/longbaby5512)
- Email: [long.nv120900@gmail.com](mailto:long.nv120900@gmail.com)
- Linkedin: [Nguyễn Văn Long](https://www.linkedin.com/in/nguyenvanlong)
- Phone: [+84 972 976 843](tel:+84972976843)
