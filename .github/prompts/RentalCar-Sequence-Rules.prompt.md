## Sequence Diagram:
在請依照目前的 Use Case 設計，接續設計 Sequence Diagram，一樣使用 Mermaid Script 語法，設計租車用戶可進行線上租車的 Sequence Diagram，(租車用戶/Actor) 可呼叫 ToRentalCar() 方法線上租用車輛 ，但在租用車輛之前，得先對 Account 領域物件，呼叫註冊帳號 RegisterAccount() 的方法，且在租車之前，得先以個人的註冊帳號 UserID 進行登入後，才可租用車輛。

並且在租用車輛之前，得先對 Account 領域物件 呼叫註冊帳號 RegisterAccount() 的方法。