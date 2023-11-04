# Deploying a Smart Contract

The **_[Remix Online IDE](https://remix.ethereum.org/)_** provides all the facilities to deploy your new smart contract directly to the blockchain. This portion of the guide walks through deploying your smart contract on the **_[Flare Network](https://flare.network)_**.

<br>
<hr>

1. Select the Solidity compiler tab from the sidebar of Remix.
    <br>
    ![Select the compiler tab](images/deploying_smart_contract/small/1_select_compiler.png){ loading=lazy width="600" }
2. Click the **Compile HelloWorld.sol** button.
    <br>
    ![Compile the smart contract](images/deploying_smart_contract/small/2_compile_code.png){ loading=lazy width="600" }
    <br>
    If you have any errors or typos, be sure to fix them.
   <br><br>
3. Select the **Deploy & run transactions** tab from the sidebar of Remix.
    <br>
    ![Select the deploy tab](images/deploying_smart_contract/small/3_select_deploy.png){ loading=lazy width="600" }
4. In the **ENVIRONMENT** drop down box, select **Injected Provider - MetaMask**. 
    <br>
    ![Select injected provider](images/deploying_smart_contract/small/4_select_injected_provider.png){ loading=lazy width="600" }
    <br>
    This should spring MetaMask into action. Ensure that the account with your 100 **C2FLR** is selected and click **Next**.
    <br>
    ![Approve connection to MetaMask](images/deploying_smart_contract/small/4b_select_injected_provider_metamask.png){ loading=lazy width="600" }
    <br>
    Allow Remix to connect to MetaMask by clicking **Connect**.
    <br>
    ![Approve connection to MetaMask](images/deploying_smart_contract/small/4c_connect_metamask.png){ loading=lazy width="600" }
    <br>
    Remix should now be able to connect with and communicate with MetaMask. Remix will utilize MetaMask to sign transactions with your address. You should see your address in the Remix sidebar under **ACCOUNT**.
    <br>
    ![Metamask connected](images/deploying_smart_contract/small/4d_metamask_connected.png){ loading=lazy width="600" }
    <br><br>
5. Type an **initialMessage** into the text field prior to deployment. Click the **Deploy** button and confirm the **CONTRACT DEPLOYMENT** transaction in MetaMask.
    <br>
    ![Metamask connected](images/deploying_smart_contract/small/5_deploy.png){ loading=lazy width="600" }
    <br>
    ![Confirm deployment](images/deploying_smart_contract/small/5b_confirm_deployment.png){ loading=lazy width="600" }
    <br>
    If all goes well, you should see several indications that your smart contract was successfully deployed.
    <br>
    ![Successful deployment](images/deploying_smart_contract/small/5c_contract_deployed.png){ loading=lazy width="600" }
    <br>
    Click on the down arrow next to the **DEBUG** button to see some information about your smart contract, including the smart contract address.
    <br><br>
    You can also see the contract name in the left sidebar.  Copy the smart contract address and paste it into the **Search** field on the **[Coston2 Blockchain Explorer](https://coston2-explorer.flare.network/)** to find your smart contract on the blockchain.
    <br>
    ![View contract on the Blockchain Explorer](images/deploying_smart_contract/small/5d_view_blockchain_explorer.png){ loading=lazy width="600" }
    <br>