# πͺ μ€ν λ§μΌ

- μλ²μ λ€νΈμνΉνμ¬ λ§μΌμ μνλ€μ λ°μμ λ³΄μ¬μ£Όλ μ΄νμλλ€.

## π λͺ©μ°¨
1. [ν μκ°](#-ν-μκ°)
2. [κΈ°λ₯ μκ°](#-κΈ°λ₯-μκ°)
3. [Diagram](#-diagram)
4. [ν΄λ κ΅¬μ‘°](#-ν΄λ-κ΅¬μ‘°)
5. [νμλΌμΈ](#-νμλΌμΈ)
6. [νλ‘μ νΈμμ κ²½ννκ³  λ°°μ΄ κ²](#-νλ‘μ νΈμμ-κ²½ννκ³ -λ°°μ΄-κ²)
7. [νΈλ¬λΈ μν](#-νΈλ¬λΈ-μν)
8. [μ°Έκ³  λ§ν¬](#-μ°Έκ³ -λ§ν¬)

## π± ν μκ°
 |[inho](https://github.com/inho-98)|[Hamo](https://github.com/lxodud)|[Jeremy](https://github.com/yjjem)|
 |:---:|:---:|:---:|
| <a href="https://github.com/inho-98"><img width="180px" src="https://user-images.githubusercontent.com/71054048/188081997-a9ac5789-ddd6-4682-abb1-90d2722cf998.jpg"></a>| <a href="https://github.com/lxodud"><img width="180px" src="https://i.imgur.com/ydRkDFq.jpg"></a>|<a href="https://github.com/yjjem"><img width="180px" src="https://i.imgur.com/RbVTB47.jpg"></a>|

## π  κΈ°λ₯ μκ°

|<img src="https://i.imgur.com/wqyWvRe.gif" width=180>|<img src="https://i.imgur.com/gyog05D.gif" width=180>| <img width="180px" src="https://i.imgur.com/G0zbobk.gif">|
|:-:|:-:|:-:|
|λ¦¬μ€νΈ μ€ν¬λ‘€ νλ©΄|λ¦¬μ€νΈμ κ·Έλ¦¬λ νλ©΄ μ ν|κ·Έλ¦¬λ μ€ν¬λ‘€ νλ©΄|

|<img src="https://i.imgur.com/nrZp4Ow.gif" width=180>|<img src="https://i.imgur.com/qqYShuX.gif" width=180>| <img width="180px" src="https://i.imgur.com/rz0aGIy.gif">|
|:-:|:-:|:-:|
|μν λ±λ‘ νλ©΄|ν€λ³΄λ νμμ νλ©΄ μ΄λ|μ΄λ―Έμ§ μΆκ° λ° μ­μ λ²νΌ κ΅¬ν|


## π Diagram

|<img width=900, src="https://i.imgur.com/GDJh1Su.png">|
|---|

## π ν΄λ κ΅¬μ‘°
```
OpenMarket
βββ Model
β   βββ Error
β   β   βββ NetworkError.swift
β   β   βββ ErrorManager.swift
β   β   βββ UserInputError.swift
β   βββ Network
β   β   βββ URLSessionProtocol.swift
β   β   βββ NetworkManager.swift
β   β   βββ UsetInputError.swift
β   β   βββ NetworkRequest.swift
β   βββ DTO
β   β   βββ ProductData.swift
β   β   βββ ProductListData.swift
β   β   βββ PostProduct.swift
β   β   βββ Currency.swift
β   β   βββ VendorData.swift
β   β   βββ ImageData.swift
β   βββ View
β   β   βββ GridCell.swift
β   β   βββ ListCell.swift
β   β   βββ ProductFormView
β   β   βββ RegistrationImageCell.swift
β   βββ Controller
β   β   βββ AppDelegate.swift
β   β   βββ SceneDelegate.swift
β   β   βββ OpenMarketViewController.swift
β   β   βββ ProductRegistrationViewController.swift
β   β   βββ ProductEditViewController.swift
β   β   βββ ProductDetailViewController.swift
β   βββ TestDouble
β   β   βββ DummyData
β   β   βββ StubURLSessionDataTask
β   β   βββ StubURLSession
β   βββ OpenMarketTests
β       βββ StubURLSessionTest
β       βββ ProductListDataTest
βββ Assets
βββ Info.plist
βββ README.md
```


## β° νμλΌμΈ

|λ μ§|κ΅¬ν λ΄μ©|
|--|--| 
|22.11.15|<`step1` μμ>`ProductData`, `ProductListData`, `VendorData`, `ImageData` `DTO`νμ κ΅¬ν, λ€νΈμνΉμ λ΄λΉν  `NetworkManager`νμ κ΅¬ν, `UnitTest`μμ± |
|22.11.16|`OpenMarketError`νμ κ΅¬ν, `TestDouble`μ μν `Dummuy`,`Stub`κ΅¬ν|
|22.11.17|`StubURLSessionTest`μμ±, μ κ·Όμ μ΄ λ° νμΌλΆλ¦¬|
|22.11.18|`NetworkManager`μ΄κ±°νμ μ°κ΄κ° μ μ© λ° urlμ λ§€κ°λ³μ μ λ¬, νμ€νΈ μ½λμ κ°μ μΈλν μ κ±°|
|22.11.22|<`step2` μμ> λ·°μ `segemented control` μΆκ°, `ProductCell`ν΄λμ€ κ΅¬ν λ° `CollectionView`κ΅¬ν|
|22.11.23|μ΄λ―Έμ§λ₯Ό κ°μ Έμ¬ λ€νΈμνΉ λ©μλ κ΅¬ν, μ λμ΄λ₯Ό μλμ μ§μ νλ `preferredLayoutAttributesFitting`λ©μλ μ¬μ μ, `cell`μ νμ€νΈμ `attributedString` μ μ©, `GridCell`ν΄λμ€ κ΅¬ν, μ»¬λ μλ·°μ gridλ μ΄μμ μΆκ°, μμ κ΅¬μ±νλ λ©μλμ κΈ°λ₯ λΆλ¦¬|
|22.11.24|μν μΆκ° λ·°λ₯Ό λ³΄μ¬μ£Όλ λ²νΌκ³Ό μ‘μ κ΅¬ν, `cell`μ μ΄λ―Έμ§ λ‘λ μ  λ‘λ© μ΄λ―Έμ§ μΆκ°, ν΄λμ€μ `final` μ μ© λ° μ κ·Όμ μ΄ μΆκ°|
|22.11.28|μ»¬λ μ λ·°μ μ€ν¬λ‘€μ΄ μ μΌ νλ¨μ λλ¬νμ λ μνμ 20κ°μ© κ°μ Έμ€λλ‘ νμ΄μ§λ€μ΄μ κ΅¬ν|
|22.11.29|`diffable dataSource`λ₯Ό μ¬μ©νκ³  `CollectionViewμ layout`μ λ³κ²½νμ λ λ°μνλ λ²κ·Έ μμ |
|22.12.01|Post μμ ν€λ, λ°λλ₯Ό κ΅¬μ±νλ λ©μλ κ΅¬ν|
|22.12.05|`ProductRegistrationView`, `imagesCollectionView layout`, `RegistrationImageCell` κ΅¬ν|
|22.12.06|ν€λ³΄λ μ λ¬΄μ λ°λ₯Έ UI μλ°μ΄νΈ, ProductEditViewController κ΅¬ν|
|22.12.07|μ΄λ―Έμ§ μΊμ±, μ΄λ―Έμ§ λ¦¬μ¬μ΄μ§ κ΅¬ν|
|22.12.08|μν λ±λ‘μ λ°μνλ μλ ₯ μλ¬ μ²λ¦¬, μν λ±λ‘ μ€ μ΄λ―Έμ§ μ­μ κΈ°λ₯ κ΅¬ν|

<details>
<summary> Details - κ΅¬ν λ΄μ©κ³Ό κΈ°λ₯ μ€λͺ </summary>

### STEP 1-1
#### 1οΈβ£ `DTO`
- λ°μ΄ν°λ₯Ό μ λ¬λ°μ νμλ€μ κ΅¬ννμ΅λλ€. κ° νμμ μ΄λ¦ λ€μλ λ°μ΄ν°λ₯Ό μ λ¬λ°μ λͺ©μ μμ λͺμνκΈ° μν΄ `Data`λ₯Ό ν¬ν¨ν©λλ€.
    - `ProductListData`
    - `ProductData`
    - `VendorData`
    - `ImageData`

#### 2οΈβ£ `DummyData`
- λ€νΈμν¬μ λ¬΄κ΄ν νμ€νΈλ₯Ό μμ±νκΈ° μν΄ Test Doubleμ μμ±

#### 3οΈβ£ `StubURLSession`
 
### STEP 1-2
#### 1οΈβ£ `UICollectionViewCompositionalLayout`
- μ»¬λ μλ·°μ λ μ΄μμμ κ΅¬μ±ν λ, `CompositionLayout`κ°μ²΄λ₯Ό μ΄μ©νμ¬ κ΅¬ννμ΅λλ€.
- λ¦¬μ€νΈ νμμ `ListConfiguration`μ κ·Έλ¦¬λ νμμ `CompositionalLayout`κ³Ό μΉμμ μ΄μ©ν΄μ κ΅¬ννμμ΅λλ€.

#### 2οΈβ£ `ListCell & GridCell`
- `ListCell`μ `UICollectionViewListCell`μ μμλ°μ `UIListContentView`μμ μ κ³΅νλ κΈ°λ³Έ μ νμμ κ΅¬μ±μ μ΄μ©ν©λλ€.
- `GridCell`μ μ»€μ€ν μλ‘ νμν λ·°λ€μ μκ΅¬μ¬ν­κ³Ό μΌμΉνκ² κ΅¬μ±ν©λλ€.

#### 3οΈβ£ `UICollectionView.CellRegistration`
- `CellRegistration`μ μ΄μ©νμ¬ μ»¬λ μλ·°μ μμ λ±λ‘νκ³ , κ° μμ κ΅¬μ±νλ μ­ν μ μνν©λλ€. μ λ€λ¦­νμμΌλ‘ μ λ¬ν μκ³Ό λ°μ΄ν° νμμΌλ‘ μμ κ΅¬μ±νκ³ , `registration`νΈλ€λ¬μμ μμ νλ‘νΌν°μ κ°μ μ§μ ν©λλ€.

#### 4οΈβ£ `UICollectionViewDiffableDataSource`
- μ»¬λ μλ·°μ λ°μ΄ν° μμ€ κ°μ²΄λ‘λ `DiffableDataSource`λ₯Ό μ΄μ©νμμ΅λλ€.

### STEP 2-1
#### 1οΈβ£ `ProductFormView`
- μν λ±λ‘κ³Ό μν μμ μ μ¬μ©λλ μμμ κ΅¬νν λ·°μλλ€.
    - μΆκ°λ  μ΄λ―Έμ§μ μ΄λ―Έμ§ μΆκ° λ²νΌμ `imagesCollectionView`μ `cell`λ‘ λ³΄μ¬μ€λλ€.
    - μνμ μ΄λ¦, κ°κ²©, μ¬κ³  λ±μ `textField & textView`λ‘ μλ ₯λ°μ΅λλ€.
    - μ μ²΄ μμλ€μ `scrollView`μμ ν¬ν¨νμ¬ μ»¨νμΈ κ° νλ©΄μ μ΄κ³Όνλ©΄ μ€ν¬λ‘€ κ°λ₯νλλ‘ κ΅¬ννμμ΅λλ€.

#### 2οΈβ£ `ProductRegistrationViewController`
- μν λ±λ‘μ μν λ·°μ»¨νΈλ‘€λ¬ μλλ€.
    - λ·°μ μλ ₯λ°μ μμλ€μ νμΈνκ³ , μ‘°κ±΄μ΄ μΆ©μ‘±λλ€λ©΄ `Done`λ²νΌμ λλ μλ μν λ±λ‘νλ `registerProduct`λ©μλκ° μ€νλ©λλ€.

#### 3οΈβ£ `ProductEditViewController`
- μν μμ μ μν λ·°μ»¨νΈλ‘€λ¬μλλ€.
    - μν λ±λ‘κ³Ό κ°μ μμμΌλ‘ μ΄λ£¨μ΄μ§ λ·°λ₯Ό λ³΄μ¬μ£Όμ§λ§, μ΄κΈ°νλ©΄μ μμ λλ μλ ν΄λΉ μμ μν μ λ³΄λ₯Ό μ΄λ―Έμ§, νμ€νΈνλ λ±μ μΆκ°ν μνλ‘ λ³΄μ¬μ§κ² λ©λλ€.
    - μμ κ³Ό μ­μ  κ³Όμ μ κ°μΈλ²€λ μ λ³΄μ μΌμΉν λ μ§νν  μ μλ€κ³  μκ°νμ¬, νμ¬μλ `Done`λ²νΌμ μ‘μμ μΆκ°νμ§ μμκ³  λ€μ μ€νμμ κΈ°λ₯μ κ΅¬νν  μμ μλλ€.

</details>

## β νλ‘μ νΈμμ κ²½ννκ³  λ°°μ΄ κ²
- CompositionalLayoutμ μ΄μ©ν λ¦¬μ€νΈ κ΅¬ν  
    βοΈ UICollectionLayoutListConfiguration  
    βοΈ UICollectionViewListCell  
    βοΈ preferredLayoutAttributesFitting  
    βοΈ UICollectionViewDiffableDataSource  
- CompositionalLayoutμ μ΄μ©ν κ·Έλ¦¬λ κ΅¬ν  
    βοΈ UICollectionViewCell  
    βοΈ UICollectionViewCompositionalLayout  
    βοΈ UICollectionViewDiffableDataSource  
- Segmented Control μ μ©κ³Ό νμ©  
    βοΈ UISegmentedControl  
    βοΈ addTarget  
- Post  
    βοΈ `multipart/form-data`μ κ΅¬μ‘° νμ  
    βοΈ `http request` κ΅¬μ‘° νμ  
    βοΈ `uploadTask` λ©μλ μ¬μ©  
- Caching  
    βοΈ `NSCache`  
    βοΈ `URLCache`
- Keyboard μ λ¬΄μ λ°λΌ λμ μΌλ‘ UIμλ°μ΄νΈ  
    βοΈ `Notification Center`  
    βοΈ `ImagePickerController`  
    βοΈ νμ€νΈνλμ μλ ₯κ°μ λ°λ₯Έ ν€λ³΄λ μ€μ   
    βοΈ μ€ν¬λ‘€λ·°μ `Content Inset`  
     
## π νΈλ¬λΈ μν
## STEP 1-1
### 1οΈβ£ λ‘μ»¬μ JSON (νμ€νΈν λ μ¬μ©ν )ν€ κ°κ³Ό APIλ¬Έμ μμ ν€ κ°μ΄ λ€λ₯Έ λ¬Έμ 
|<img src="https://i.imgur.com/4Kl6HGR.png" width="300px"/> | <img src="https://i.imgur.com/cpGzC9E.png" width=500px/>|
|:-:|:-:|
|`APIλ¬Έμμ ν€ κ°`|`λ‘μ»¬ JSONνμΌμ ν€κ°`|

- μλ²(pageNo)μ JSON(page_no)μ νμ¬ νμ΄μ§ λ²νΈμ keyκ°μ΄ μΌμΉνμ§ μλ λ¬Έμ μ μ΄ μμμ΅λλ€. 
μ½λ©ν€λ₯Ό `pageNO`λ‘ μμ±νλ©΄ `JSON`νμΌμ λμ½λ©ν  μ μμμ΅λλ€.
μ΄λ₯Ό ν΄κ²°νκΈ° μν΄ μλ²μ ν€μ JSONν€ λͺ¨λ `camelCase`λ‘ λ³ννλ νλ‘νΌν°λ₯Ό μ¬μ©νμ΅λλ€.

    ```swift
    let decoder = JSONDecoder()
    decoder.keyDecodingStrategy = .convertFromSnakeCase                 
    ```
ν΄λΉ νλ‘νΌν°λ₯Ό μ¬μ©ν¨μΌλ‘μ¨ μλμ κ°μ΄ λ€μ΄μ€λ `vendor_id` ν€ κ°μ μΉ΄λ©μΌμ΄μ€λ‘ λ³ννμ¬ μνλ μΌμ΄μ€ λ€μμΌλ‘ μμ ν  μ μμμ΅λλ€.
|||
|--|--|
|APIλ¬Έμμ ν€|![](https://i.imgur.com/gFcg0AL.png)|
|μ½λλ‘ κ΅¬νν ν€|`case vendorIdentifier = "vendorId"`|

### 2οΈβ£ κ°μ μν μμΈμ λν΄μ μκ΅¬νλ ν€κ°μ΄ μλ‘ λ€λ₯Έ λ¬Έμ 
- μλ²μ μν λ¦¬μ€νΈ μ‘°ν, μν μμΈ μ‘°ν λ κ°μ§ μμ²­μ λ³΄λΌ λ λ°μμ€λ JSONνμΌμ ν€κ° μΌμΉνμ§ μμμ ProductData DTOλ₯Ό μ€λ³΅μΌλ‘ μ¬μ©νμμ λ λμ½λ©μ΄ λμ§ μλ λ¬Έμ κ° μμμ΅λλ€.
- `ProductList`μμλ `Product`μ `description`κ³Ό `vendorName`μ μκ΅¬νκ³ ,
`Product`μμΈμμλ `images`μ `vendors`λ₯Ό μκ΅¬νλ λΆλΆμ μ΄λ»κ² ν΄κ²°ν μ§ κ³ λ―Όνμ κ²ΉμΉμ§ μλ ν€μ ν΄λΉνλ νλ‘νΌν°λ₯Ό μ΅μλ μ²λ¦¬νμ¬ ν΄κ²°νμμ΅λλ€.

  ```swift
  struct ProductData: Decodable {    
      ...
      let vendorName: String?
      let description: String?
      let images: [ImageData]?
      let vendors: VendorData?
  }
  ```

### 3οΈβ£ λΉλκΈ°λ‘ λμνλ `dataTask`κ° λλ μμ μ λ°μ΄ν°λ₯Ό λ°λ λ°©λ²
- `NetworkManager`μ `loadData`λ©μλ λ΄λΆμμ νΈμΆνλ `dataTask` λ©μλλ νλΌλ―Έν°μΈ `completionHandler`λ₯Ό μ΄μ©νμ¬ `data, response, error`λ₯Ό λ°μ μ μλλ° λΉλκΈ°μ μΌλ‘ λμνκΈ° λλ¬Έμ λλλ μμ μ μμμμ΄μ λ°μμ¨ λ°μ΄ν°λ₯Ό μ΄λ»κ² μ λ¬ν μ§ κ³ λ―Όμ΄μμ΅λλ€.
- `loadDataμ` νλΌλ―Έν°λ‘ `escaping closure`λ₯Ό λ°μμ `dataTask`μ `completionHandler`κ° ν΄λΉ ν΄λ‘μ λ₯Ό μΊ‘μ²νμ¬ λΉλκΈ°μ μΌλ‘ μμμ΄ λλ μμ μ μΊ‘μ²ν ν΄λ‘μ λ₯Ό νΈμΆνλ λ°©λ²μΌλ‘ ν΄κ²°νμμ΅λλ€.

    ```swift
    func loadData<T: Decodable>(of request: NetworkRequest,
                                dataType: T.Type,
                                completion: @escaping (Result<T, Error>) -> Void) {
        guard let url = request.url else { return }

        session.dataTask(with: url) { data, response, error in
            ...

            do {
                ...
                let data = try decoder.decode(T.self, from: data)
                completion(.success(data))
            } catch {
                completion(.failure(OpenMarketError.failedToParse))
            }
        }.resume()
    }
    ```


### 4οΈβ£ `Test Double`μμμ μ½λ νλ¦κ³Ό νμ€νΈλ₯Ό μν΄ κ΅¬νν νμλ€
- λ€νΈμν¬κ° μλ νκ²½μμλ νμ€νΈλ₯Ό μννκΈ° μν΄μ λ€νΈμνΉμ μννλ `URLSession`κ³Ό `URLSessionDataTask`λμ νλ `Stub`κ°μ²΄λ₯Ό κ΅¬ννμ΅λλ€. κ·Έλμ `DummyData`λ₯Ό λ§λ€μ΄λκ³  μ΄λ₯Ό `dataTask`μ `completionHandler`κΉμ§ μ λ¬ν©λλ€.

    ```swift
    //νμ€νΈ μ½λ μμ
    func test_productListDataλ₯Όλ°μμλ_μ λ¬λ°μκ°μ_λ¦¬ν΄ν΄μΌνλ€() {
        //given
        guard let url = NetworkRequest.productList.url else { return }

        let expectedData = """
                        {
                            ...
                            "totalCount": 116,
                            ...
                            
                            """.data(using: .utf8)
        let response = HTTPURLResponse(url: url,
                                       statusCode: 200,
                                       ...)
        let dummyData = DummyData(data: expectedData,
                                  response: response,
                                  error: nil)
        stubUrlSession.dummyData = dummyData

        //when
        sut.loadData(of: NetworkRequest.productList,
                        dataType: ProductListData.self) { result in
            switch result {
            case .success(let productListData):
            //then
                XCTAssertEqual(productListData.totalCount, 116)
            case .failure(let error):
                XCTFail("loadData failure: \(error)")
            }
        }
    }
    ```
    
    - μ μμμμ, λ°μμ¬ κ²μ΄λΌκ³  μμλλ λ°μ΄ν°λ₯Ό μμ±νκ³ , μλ΅μ΄ μ±κ³΅νλ€κ³  κ°μ ν΄μ μ±κ³΅νλ`response`λ₯Ό μμ±νμμ΅λλ€. μ΄ μ λ³΄λ€μ `dummyData`μ ν¬ν¨νμ¬ κ°μ§ κ°μ²΄μΈ `stubUrlSession`μ μ λ¬νκ³ , `NetworkManager`μ `loadData`λ©μλλ₯Ό νΈμΆν΄μ μλν κ²°κ³Όμ μΌμΉνλμ§ νμΈν©λλ€.
## STEP 1-2
### 1οΈβ£ λͺ¨λ μ»¬λ μλ·°λ₯Ό μ΄μ©ν μ»¬λ μλ·° κ΅¬ν
- μ»¬λ μ λ·°λ₯Ό κ΅¬νν λ, `flowLayout`κ³Ό `dataSource` λμ , `composableLayout`κ³Ό `diffableDataSource`λ₯Ό μ΄μ©ν΄μ κ΅¬ννμμ΅λλ€. 
- `snapshot`μ λ·°μ λ°μ΄ν°μ νΉμ  μμ μ μνλ₯Ό λνλ΄κ³  μΉμλ³λ‘ λλμ΄μ μνλ μΉμκ³Ό μμ΄νμΌλ‘ κ΅¬μ±νκ³ , `dataSource`μ `apply`λ©μλλ₯Ό μ΄μ©νμ¬ `snapshot`μ λ°μ΄ν°λ₯Ό νμ¬ `state`μ μ stateλ₯Ό λΉκ΅νμ¬ μλ°μ΄νΈν©λλ€.
- μ νμ `Implementing Modern Collection Views`λ₯Ό κΈ°λ°μΌλ‘ `Customize List Cells`λ₯Ό κ΅¬ννλ €νμ΅λλ€. 
- μ΄λ `custom`ν `state`λ₯Ό λ§λ€μ΄μ νμ©ν  μ μλλ°, μ΄λ² νλ‘μ νΈμμλ μμμ μ ν, νμ΄λΌμ΄νΈ, μ΄λ λ±μ μνμ λ°λ₯Έ λ³κ²½μ΄ μμ΄μ `custom state`λ₯Ό μ¬μ©ν  νμμ±μ΄ μλ€κ³  μκ°νμ¬ μ μΈνμμ΅λλ€.

### 2οΈβ£ `UICollectionViewListCell`μ ν¬κΈ°λ₯Ό μ»€μ€νμΌλ‘ μ§μ νλ λ°©λ²
- `list`ννμ `collectionView`λ₯Ό `cell`μ΄ κΈ°λ³Έμ μΌλ‘ μ κ³΅νλ λ μ΄μμμ μ΄μ©νμ¬ μλ μ½λμ²λΌ κ°νΈνκ² λ§λ€μμ΅λλ€.
κ·Έλ°λ° μμ΄ `self-sizing`μ νμ¬μ ν΄λ¦­λμμ λ μλμΉ μκ² λμ΄κ° λμ΄λλ λ¬Έμ κ° λ°μνμ΅λλ€.
μ΄λ₯Ό μμ΄ λ μμ΄μμ μ λ¬λκΈ° μ μ μλμΌλ‘ ν¬κΈ°λ₯Ό μ‘°μ ν  μ μλλ‘ νλ`preferredLayoutAttributesFitting()` λ©μλλ₯Ό μ΄μ©ν΄μ μ»€μ€νν `cell size`λ₯Ό μ ν΄μ£Όμ΄ ν΄κ²°νμμ΅λλ€.
    ```swift
    let configure = UICollectionLayoutListConfiguration(appearance: .plain)
    let layout = UICollectionViewCompositionalLayout.list(using: configure)
    ```

### 3οΈβ£ μΈκ·Έλ¨ΌνΈ μ»¨νΈλ‘€μ μ΄μ©νμ¬ νλ©΄μ νμ μ»¬λ μλ·°κ° μ€μ²©λλ λ¬Έμ 
|<img src="https://i.imgur.com/orXxNVB.jpg" width=600>|
|--|
- μΈκ·Έλ¨ΌνΈ μ»¨νΈλ‘€μ κ°μ λ°λΌ `grid` λ μ΄μμ, `list` λ μ΄μμμ κ°μ§λ μ»¬λ μ λ·°λ₯Ό λ€μ κ·Έλ €μ `viewControllerμ` `root view`μ `addSubview`νμ¬ νλ©΄μ΄ μ νλλλ‘ κ΅¬ννμ΅λλ€.
- μ΄λ κΈ°μ‘΄μ μλ `collectionView`κ° μ¬λΌμ§μ§ μκ³  μ€μ²©λλ λ¬Έμ κ° μμμ΅λλ€.
- `productCollectionView` λ³μμ μλ‘μ΄ `collectionView`λ₯Ό ν λΉνκΈ° λλ¬Έμ μ°Έμ‘°κ° μ¬λΌμ Έμ `deinit`λ κ±°λΌ μκ°νλλ° `UIViewμ` `addSubView`λ₯Ό μ¬μ©νλ©΄ μΆκ°ν λ·°λ₯Ό κ°νκ² μ°Έμ‘°νμ¬μ `deinit`λμ§ μλλ€λ μ μ νμΈνκ³ , μμ μ μμ λ·°λ‘λΆν° ν΄μ νλ `removeFromSuperview()` λ©μλλ₯Ό μ¬μ©νμ¬ ν΄κ²°νμμ΅λλ€.

### 4οΈβ£ μμ λΉ λ₯΄κ² μ€ν¬λ‘€νμλ μμ λ°μ΄ν°μ μΌμΉνμ§ μλ μ΄λ―Έμ§κ° λ‘λλλ λ¬Έμ 
- λ€νΈμνΉμ ν΅ν΄μ μμ μ΄λ―Έμ§λ₯Ό μλ²μμ κ°μ Έμ€λλ° λΉ λ₯΄κ² μ€ν¬λ‘€νμ λ μμ μ΄λ―Έμ§κ° μ¬λ¬λ² λ°λλ λ¬Έμ κ° μμμ΅λλ€.
- μμ΄ μ¬μ¬μ©λ  λλ§λ€ μ΄λ―Έμ§λ₯Ό κ°μ Έμ€λ μμμ΄ μμ±λκ³  μ¬λ¬κ°μ μμλ€μ΄ λλ λλ§λ€ μμ μ΄λ―Έμ§λ₯Ό λ°κΎΈκΈ° λλ¬Έμ λ°μνλ λ¬Έμ μμ΅λλ€.
- λ€νΈμνΉ μμμ μμ±νλ μμ μ `indexPath`μ νμ¬ `cell`μ `indexPath`λ₯Ό λΉκ΅νμ¬ λ κ°μ΄ κ°μ κ²½μ°μλ§ μ΄λ―Έμ§λ₯Ό λ³κ²½νμ¬ ν΄κ²°νμμ΅λλ€.
    ```swift
    if indexPath == self.productCollectionView.indexPath(for: cell) {
        cell.imageView.image = image
    }
    ```
### 5οΈβ£ `Diffable Datasource` μΈμ€ν΄μ€λ₯Ό λ§λ€ λ ν΄λ‘μ  λ΄λΆμμ `Cell Registration`μ μμ±ν  λ λ°μνλ μλ¬
![](https://i.imgur.com/OS0QY97.png)
- `CellRegistrationμ diffabel datasource` ν΄λ‘μ  λ΄λΆμμ λ§λ€λ©΄ μ κ·Έλ¦Όκ³Ό κ°μ μλ¬κ° λ°μνλ€.
- μ΄ λΆλΆμ λν΄μ `UICollectionView.CellRegistration` κ³΅μλ¬Έμμ λͺμλμ΄ μλλ° μλ κ·Έλ¦Όκ³Ό κ°λ€.

![](https://i.imgur.com/evOUc3i.png)
- λ°λΌμ μΈλΆμμ `CellRegistration` μΈμ€ν΄μ€λ₯Ό μμ±νκ³  ν΄λ‘μ  λ΄λΆμμ μ¬μ©νμ¬ λ¬Έμ λ₯Ό ν΄κ²°νμλ€.
    
## STEP 2-1
### 1οΈβ£ μν λ±λ‘μ μν `PostData`λ©μλ κ΅¬ν
- μν μ λ³΄μ μ΄λ―Έμ§ νμΌμ ν¬ν¨νκ³  μκΈ° λλ¬Έμ `POST`μ `multipart/form-data`νμμ μ΄ν΄ν΄μΌ νμ΅λλ€.
- νμμ λ§κ² `request`μ ν€λμ λ°λλ₯Ό κ΅¬μ±νκ³ , μ΄λ―Έμ§λ₯Ό λ°μ΄ν° νμμΌλ‘ λ°λμ μΆκ°ν ν μ΄λ₯Ό `uploadTask`λ©μλμ λ§€κ°λ³μλ‘ μ λ¬ν©λλ€. (`request & data`)

### 2οΈβ£ μν λ±λ‘ νλ©΄μμ μ¬μ§ κ°μμ λ°λ₯Έ `imagePicker` κ΅¬ν?
- μν λ±λ‘ νλ©΄μμ μ¬μ§μ μ ννκΈ° μν λ°©λ²μΌλ‘ `phpickerViewController`μ `imagePickerViewController` 2κ°μ§κ° μμ΅λλ€.
- μκ΅¬μ¬ν­μ μ νλ μ¬μ§μ `crop`νλ κΈ°λ₯μ΄ μΆκ°λμ΄μΌ νλλ° `phpickerViewController`μ κ²½μ° `crop` κΈ°λ₯μ΄ μκΈ° λλ¬Έμ `imagePickerViewController`λ₯Ό μ ννμμ΅λλ€.

### 3οΈβ£ ν€λ³΄λ λμ΄λ§νΌ μ€ν¬λ‘€λ·° μ¬λ¦¬κΈ°
- νμ€νΈλ·°μ μλ ₯μ ν  λ ν€λ³΄λκ° μ¬λΌμμ νλ©΄μ κ°λ¦¬λ λ¬Έμ κ° μμ΄μ ν€λ³΄λκ° μ¬λΌμμ λ ν€λ³΄λ λμ΄λ§νΌ `scrollView`μ `contentOffSet`μ λμ¬μ£Όμμ΅λλ€.
- `contentOffSet`μ μ‘°μ νμ¬λ `content`μ `height`κ° μ¦κ°νλκ² μλκΈ° λλ¬Έμ μ€ν¬λ‘€νκ±°λ νμ΄νμ νκ±°λ μ€ν¬λ‘€νμ λ `contentOffSet`μ΄ μ΄μ μΌλ‘ λ³νλ λ¬Έμ κ° λ°μνμ΅λλ€.
- `scrollView`μ `contentInset`μ μ΄μ©νμ¬ ν€λ³΄λκ° μ¬λΌμ¬ λ κ·Έ λμ΄ λ§νΌμ μ¬λ°±μ μ£Όκ³  λ΄λ €κ° λ λ€μ 0μΌλ‘ λ§λ€μ΄μ£Όμ΄μ ν΄κ²°νμμ΅λλ€.

### 4οΈβ£ μν λ±λ‘, μμ  λ·°μμ νμ€νΈ νλ, νμ€νΈ λ·°λ₯Ό μ μΈν κ³³μ ν°μΉνμ λ ν€λ³΄λ λ΄λ¦¬κΈ°
- ν°μΉ μ΄λ²€νΈκ° `responder chain`μ νκ³  λ΄λ €μ€κΈ° λλ¬Έμ `viewController`μμ μ΄λ²€νΈλ₯Ό μ²λ¦¬νλ `touchBegan`μ μ¬μ μνμ¬ λ΄λΆμμ `endEditing`μ νΈμΆνλ € νμλλ° νΉμ  λΆλΆμμλ `viewController`κ° μ΄λ²€νΈλ₯Ό μ²λ¦¬νμ§ λͺ»νλ μν©μ΄ λ°μνμμ΅λλ€.
- ν΄λΉ λ·°μμ `viewController`μμ `scrollView`κ° μκ² κ·Έ μμ `contentView`κ° μλ κ³μΈ΅μ΄μκ³  ν°μΉ μ΄λ²€νΈλ₯Ό `scrollView`κ° κ°μ Έκ°κΈ° λλ¬Έμ `viewController`μμ μ΄λ²€νΈλ₯Ό μ²λ¦¬νμ§ λͺ»νλ λ¬Έμ μμ νμνκ³  `scrollView`μ `gesture`λ₯Ό μΆκ°νμ¬ ν°μΉ μ΄λ²€νΈκ° λ°μνμ λ `endEditing`νλλ‘ νμμ΅λλ€.

### 5οΈβ£ μ μ μ μλ ₯μ νμΈνλ κ³Όμ  λ° POST μλ μ ν
- `ProductFormView`μμ κ°κ°μ `TextField`μ μκ΅¬μ¬ν­ μΆ©μ‘± λ° νμμ νμΈνλ μ°μ° νλ‘νΌν°λ₯Ό κ΅¬ννμ΅λλ€.
- μν λ±λ‘ μ‘°κ±΄μ μΆ©μ‘±νμ§ μμΌλ©΄ `nil`μ λ°ννλλ‘νμ¬ κ°μ΄ `nil`μ΄λ©΄ `POST`κ° μ§νλμ§ μλλ‘ κ΅¬ννμ΅λλ€.
```swift
var nameInput: String? {
    guard let text = productNameTextField.text,
          (3...100).contains(text.count) else { return nil } //κΈμμ μ ν
        return text
    }
}
...
```

### 6οΈβ£ `Done`λ²νΌμ μ¬λ¬λ² λλ¬ μ€λ³΅ `POST`λλ νμκ³Ό `POST`κ° μλ£λ νμ `dismiss`μμ
- `Done` λ²νΌμ μ¬λ¬λ² λλ₯΄λ©΄ ν κ²μλ¬Όμ΄ μ¬λ¬λ² λ±λ‘λλ λ¬Έμ κ° μμμ΅λλ€. 
- μ΄λ₯Ό ν΄κ²°νκΈ° μν΄ POSTκ° μ§νλ  λ λ²νΌμ΄ νλ² λλ¦¬λ©΄ `button`μ `isEnabled` νλ‘νΌν°λ₯Ό μ΄μ©ν΄μ λΉνμ±ν λλλ‘ κ΅¬ννμμ΅λλ€.
- μν λ±λ‘νλ©΄μ λ±λ‘μ΄ μ±κ³΅μ μΌλ‘ μ§νλ νμ λ΄λ €κ°μΌ νλ€κ³  μκ°νμ¬, μλ‘λλ₯Ό μννλ `postData`μ `completion handler`λ₯Ό μΆκ°νμ¬ μμμ΄ μλ£λ νμ `dismiss`νλλ‘ κ΅¬ννμμ΅λλ€.
```swift
networkManager.postData(request: request, data: data) {
    DispatchQueue.main.async {
        self.dismiss(animated: true)
    }
}
```



## π μ°Έκ³  λ§ν¬

[κ³΅μλ¬Έμ]
- [π Closure](https://docs.swift.org/swift-book/LanguageGuide/Closures.html)
- [π URLSession](https://developer.apple.com/documentation/foundation/urlsession)
- [π URLSessionDataTask](https://developer.apple.com/documentation/foundation/url_loading_system/fetching_website_data_into_memory/)
- [π dataTask(with:completionHandler:)](https://developer.apple.com/documentation/foundation/urlsession/1410330-datatask/)
- [π uploadTask(with:from:completionHandler:)](https://developer.apple.com/documentation/foundation/urlsession/1411518-uploadtask)
- [π Fetching Website Data into Memory](https://developer.apple.com/documentation/foundation/url_loading_system/fetching_website_data_into_memory)
- [π Uploading Data to a Website](https://developer.apple.com/documentation/foundation/url_loading_system/uploading_data_to_a_website)
- [π Implementing Modern Collection Views](https://developer.apple.com/documentation/uikit/views_and_controls/collection_views/implementing_modern_collection_views)
- [π NSCache](https://developer.apple.com/documentation/foundation/nscache)
- [π URLCache](https://developer.apple.com/documentation/foundation/urlcache)
- [π URLCache.StoragePolicy](https://developer.apple.com/documentation/foundation/urlcache/storagepolicy)
- [π NSURLRequest.CachePolicy](https://developer.apple.com/documentation/foundation/nsurlrequest/cachepolicy)
- [π NSURLRequest.CachePolicy.useProtocolCachePolicy](https://developer.apple.com/documentation/foundation/nsurlrequest/cachepolicy)
- [π UIImagePickerController](https://developer.apple.com/documentation/uikit/uiimagepickercontroller)
- [π PHPickerViewController](https://developer.apple.com/documentation/photokit/phpickerviewcontroller)




[WWDC]
- [π Modern cell configuration](https://developer.apple.com/videos/play/wwdc2020/10027/)
- [π List in Collection View](https://developer.apple.com/videos/play/wwdc2020/10026)
- [π Advances in UICollectionView](https://developer.apple.com/videos/play/wwdc2020/10097/)
- [π Advances in Collection View Layout](https://developer.apple.com/videos/play/wwdc2019/215)

[κ·Έ μΈ μ°Έκ³ λ¬Έμ] 

- [π κ°λ°μ μλ€μ΄ - closureμ @escaping μ΄ν΄νκΈ°](https://babbab2.tistory.com/164)
- [π jessesquires - why optional closures in Swift are escaping](https://www.jessesquires.com/blog/2018/06/10/why-optional-swift-closures-are-escaping/)
- [π ν΄λ‘μ  μ λ³΅νκΈ°(3/3)](https://babbab2.tistory.com/83)
- [π Mockμ μ΄μ©ν UnitTest](https://sujinnaljin.medium.com/swift-mock-%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-network-unit-test-%ED%95%98%EA%B8%B0-a69570defb41)
- [π xUnit Patterns.com - Test Double](http://xunitpatterns.com/Test%20Double.html)
- [π Steven Curtis - Stubbing, Mocking or Faking](https://medium.com/swlh/stubbing-mocking-or-faking-5674a07bc3db)
