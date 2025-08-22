# Access-Control
**English:** Mechanism to restrict who can access what in a system.

**Urdu:** Ye ek system hai jo decide karta hai kon sa user kis cheez tak pohanch sakta hai.

## Authorization

**English:** After authentication, system checks what the user is allowed to do.

**Urdu:** Jab user login karta hai (authenticate hota hai) to system check karta hai us ke pass kya rights hain – file read kar sakta hai, delete kar sakta hai ya nahi.

## Authorization Creep (Privilege Creep)

**English:** Users accumulate extra permissions over time without removal of old ones.

**Urdu:** Jab user ka role change hota rehta hai aur usko naye rights milte rehte hain lekin purane rights remove nahi hote, isko authorization creep kehte hain. Ye dangerous hota hai kyunki user ke pass unnecessary zyada access hota hai.

## Least Privilege Principle

**English:** User should have minimum access needed for work.

**Urdu:** Har user ko sirf utna hi access milna chahiye jitna uski job ke liye zaruri hai, extra kuch nahi.

## Dual Control & Separation of Duties (SoD)

**Dual Control**

**English:** Two people required for sensitive action.

**Urdu:** Agar koi critical kaam karna ho jaise bank transfer, to do log approve karein tabhi complete hoga.

## Separation of Duties (SoD)

**English:** Split important tasks between people.

**Urdu:** Koi ek banda full control na rakhe – jaise ek banda request kare, doosra approve kare, teesra process kare.

## Access Control Models

 **RBAC (Role-Based Access Control)**	Access based on user’s role.
 **Urdu** Agar banda "Manager" hai to usko reports dekhne ka right hai, lekin server configure nahi kar sakta.

 **ABAC (Attribute-Based Access Control)**	Access based on attributes (user, environment, resource).	
 **Urdu** Agar user "HR dept" ka hai aur "working hours" me request kare to access milega.

 **DAC (Discretionary Access Control)**	Owner decides permissions.
 **Urdu** File ka owner khud decide karega kisko read/write access mile.

 **MAC (Mandatory Access Control)**	Based on classification levels (confidential, secret).	
 **Urdu** Military systems jahan files "Top Secret" ya "Confidential" hoti hain, aur system hi enforce karta hai access.


## Risk-Based Security Triggers

 **English:** Dynamic security checks based on situation.

**Urdu:** Jab system ko lagta hai risk zyada hai to extra security lagata hai.

**Examples:**

Login from new country → MFA mangta hai.

Zyada failed login attempts → account lock.

Office hours ke bahar access → re-authentication required.

## Summary Mix:

**Access Control** = decide karta hai user kya kar sakta hai.

**Authorization** = rights check after login.

**Authorization creep** = unnecessary extra rights.

**Least Privilege** = sirf minimum rights.

**Dual Control & SoD** = kaam ko split karna for safety.

**RBAC, ABAC, DAC, MAC** = different models of access control.

**Risk-based triggers** = system risk detect karke security ka level increase kar deta hai.
