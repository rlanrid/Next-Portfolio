# Next.js로 Thread만들기

## 작업순서
**초기세팅**
`npx create-next-app@latest .`
`npm i`

`npm install @clerk/themes`
`npx shadcn-ui@latest add form`
`npx shadcn-ui@latest init`

## 사용한 기술

## TypeScript 사용

## shadcn 사용

## uploadthing 사용

## Tailwind CSS 사용
Tailwind CSS는 유연하고 확장 가능한 CSS 프레임워크입니다. 일반적인 CSS 프레임워크와는 달리   
사전 정의된 클래스를 사용하여 스타일을 적용하는 방식으로 작동합니다.   
이 클래스들은 주로 HTML 요소에 직접 적용되어 디자인을 구성하는 데 사용됩니다.

## Clerk 사용
Clerk는 개발자가 사용자 관리와 인증 기능을 쉽게 구축할 수 있도록 도와주는 플랫폼 중 하나입니다.   
사용자 관리, 인증, 권한 부여, 프로필 관리 등을 간편하게 처리할 수 있는 도구로,   
개발자들이 보다 빠르고 안전하게 사용자 관리 기능을 구현하는 데 도움을 줍니다.

## 트러블슈팅
<details>
    <summary>
    Unhandled Runtime Error   
    Error: ClerkInstanceContext not found
    </summary>

    - 문제 원인

    
    - 문제 해결

    <html lang="en">
        <ClerkProvider>
            <body className={inter.className}>
                {children}  
            </body>
        </ClerkProvider>
    </html>
</details>

## 사이트

인증 서비스 - [clerk](https://clerk.com/)   
파일 업로드 - [uploadthing](https://uploadthing.com/)   
배포 - [vercel](https://vercel.com/)   


## 스택
