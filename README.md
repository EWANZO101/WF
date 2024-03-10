## Allowing a Port Through Windows Firewall

To allow a port through the Windows Firewall on a Windows system, follow these steps:

1. **Open Windows Defender Firewall Settings**:
   - Press the `Windows` key and type "Windows Defender Firewall". Then select "Windows Defender Firewall with Advanced Security" from the search results.
   - Alternatively, you can open Control Panel, go to "System and Security", and then click on "Windows Defender Firewall".

2. **Navigate to Inbound Rules**:
   - In the Windows Defender Firewall with Advanced Security window, click on "Inbound Rules" in the left pane. This will show a list of inbound rules currently configured on your system.

3. **Create a New Inbound Rule**:
   - In the right pane, click on "New Rule...". This will open the "New Inbound Rule Wizard".

4. **Choose Rule Type**:
   - In the "Rule Type" section, select "Port" and click "Next".

5. **Specify Protocol and Port**:
   - In the "Protocol and Ports" section, select "TCP" or "UDP" depending on the protocol used by the application/service you want to allow.
   - Select "Specific local ports" and enter the port number you want to allow (e.g., 80 for HTTP).
   - Click "Next" to continue.

6. **Choose Action**:
   - In the "Action" section, select "Allow the connection".
   - Click "Next".

7. **Choose Profiles**:
   - In the "Profile" section, select the network location types where this rule should apply. Typically, you would select all options (Domain, Private, and Public).
   - Click "Next".

8. **Specify Rule Name**:
   - Enter a name and description for the rule to help you identify it later.
   - Click "Finish" to create the rule.

9. **Verify the Rule**:
   - After creating the rule, verify that it appears in the list of inbound rules. You should see your newly created rule listed.

10. **Test Connectivity**:
    - Test the connectivity to the port you just opened to ensure that it's working as expected.
