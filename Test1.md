## This file shows the test of generating a star schema by using the datasets of TPC-C.

### 1. Schema:
![Image16](https://user-images.githubusercontent.com/43824695/100232496-b2ce6480-2f28-11eb-811d-4c3c656e809e.png)

### 2. Instance:
#### Number of tuples of S1:
![image](https://user-images.githubusercontent.com/75027258/101087682-d477bd80-35b2-11eb-9b3a-7d2875f6b5c1.png)
![image](https://user-images.githubusercontent.com/75027258/101133374-e97f3b80-3608-11eb-99ee-adf4baa2522d.png)

#### Customer of S1:
![image](https://user-images.githubusercontent.com/43824695/100223544-ed7dd000-2f1b-11eb-818f-722c35b69c7d.png)
#### Supplier of S1:
![image](https://user-images.githubusercontent.com/43824695/100223591-fd95af80-2f1b-11eb-822a-0cd1fc673bbe.png)
#### Part of S1:
![image](https://user-images.githubusercontent.com/43824695/100223625-0b4b3500-2f1c-11eb-980a-85bcbf271c86.png)
#### Orderdate of S1:
![image](https://user-images.githubusercontent.com/43824695/100223670-18682400-2f1c-11eb-9d99-377d295789c3.png)
#### Lineorder of S1:
![image](https://user-images.githubusercontent.com/43824695/100223773-39307980-2f1c-11eb-9873-e00781253b5b.png)

#### Number of tuples of S2:
![image](https://user-images.githubusercontent.com/75027258/101133415-fb60de80-3608-11eb-8cec-238be619d117.png)
![image](https://user-images.githubusercontent.com/75027258/101088704-5b796580-35b4-11eb-984d-be55d39ba17a.png)
#### Number of common tuples betweent S1 and S2:
![image](https://user-images.githubusercontent.com/75027258/101133457-0fa4db80-3609-11eb-99be-778b0692b3e8.png)

#### Customer of S2:
![image](https://user-images.githubusercontent.com/43824695/100223823-4b121c80-2f1c-11eb-95a4-282385a6a3a4.png)
#### Supplier of S2:
![image](https://user-images.githubusercontent.com/43824695/100223878-5cf3bf80-2f1c-11eb-8b22-91de74314fd5.png)
#### Part of S2:
![image](https://user-images.githubusercontent.com/43824695/100223911-65e49100-2f1c-11eb-82bf-6e0d8a14fe20.png)
#### Orderdate of S2: 
![image](https://user-images.githubusercontent.com/43824695/100223934-6e3ccc00-2f1c-11eb-8b91-eb987cd9d96d.png)
#### Lineorder of S2:
![image](https://user-images.githubusercontent.com/43824695/100223979-7ac12480-2f1c-11eb-8af4-49f5a4d7a034.png)


### 3. Test code in the program:
![image](https://user-images.githubusercontent.com/43824695/100224263-e3100600-2f1c-11eb-9d00-eb74ba743cda.png)

### 4.Result:
#### schema:
![image](https://user-images.githubusercontent.com/43824695/100224477-2bc7bf00-2f1d-11eb-89d5-22aec387b23d.png)
#### Instance:
#### Customer:
![image](https://user-images.githubusercontent.com/43824695/100224829-a1cc2600-2f1d-11eb-87a1-5b0c324befc7.png)

#### Supplier:
![image](https://user-images.githubusercontent.com/43824695/100225199-2028c800-2f1e-11eb-84ce-266cbecc0324.png)

#### Part:
![image](https://user-images.githubusercontent.com/43824695/100225303-4b131c00-2f1e-11eb-9243-c00cce5c7826.png)

#### Orderdate:
![image](https://user-images.githubusercontent.com/43824695/100233428-08efd780-2f2a-11eb-9719-e893545c739c.png)

#### Lineorder:
![image](https://user-images.githubusercontent.com/43824695/100225135-0a1b0780-2f1e-11eb-90ea-ba8942da18ad.png)

#### Number of tuples:
![image](https://user-images.githubusercontent.com/75027258/101091643-bad97480-35b8-11eb-9e4a-cb128f60ace3.png)
![image](https://user-images.githubusercontent.com/75027258/101133506-24816f00-3609-11eb-9ae9-9b244e8d0e53.png)

#### Number of completed attributes:
![image](https://user-images.githubusercontent.com/75027258/101094717-1dcd0a80-35bd-11eb-96f3-fb2457ac77d4.png)
![image](https://user-images.githubusercontent.com/75027258/101133544-3531e500-3609-11eb-9431-b4057bcf210e.png)

#### Why the hierarchy is removed
![image](https://user-images.githubusercontent.com/75027258/101097406-64bcff00-35c1-11eb-900c-dfbf24782aac.png)
![image](https://user-images.githubusercontent.com/75027258/101097453-77cfcf00-35c1-11eb-963f-617f0d2e1351.png)


