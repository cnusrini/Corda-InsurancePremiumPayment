<p align="center">
  <img src="https://www.corda.net/wp-content/uploads/2016/11/fg005_corda_b.png" alt="Corda" width="100">
</p>

#### CorDapp
Corda-InsurancePremiumPayment
* This sample allows various patients to pay their premium to the insurance company on the corda network.

#### Corda-InsurancePremiumPayment
* corDapp is built on the below versions :
  * corda_release_group = 'net.corda'
  * corda_release_version = '3.3-corda'
  * corda_gradle_plugins_version = '3.2.1'
  * kotlin_version = '1.1.60'
  * junit_version = '4.12'
  * quasar_version = '0.7.9'

#### How to get the corda code:
  * cd to your repo
  * git clone https://github.com/cnusrini/Corda-InsurancePremiumPayment.git

#### How to build in the following order
 * from with in the root directory, execute .\gradlew.bat
 * from with in the root directory, execute .\gradlew clean deployNodes
 * After successful build with in kotlin-source/build/nodes it should show 3 nodes Notary, PartyA and PartyB and few    other files.

#### To run nodes:
 * from with in the directory kotlin-source/build/nodes , execute .\runnodes.bat
 * this will spin up nodes

#### To use it:
 * from browser type http://localhost:10009 for PartyA
 * from browser type http://localhost:10012 for PartyB

#### Relaunch nodes
 * To relaunch the nodes,follow the instructions from To run nodes

#### TO DO Lists
- [ ] Building smart contract
- [ ] Building UI
- [ ] Building unit test scrits
