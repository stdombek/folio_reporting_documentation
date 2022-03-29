# Documentation: agreements_subscription_agreement.sql
- - -
Last update: 	2021-11-29  
Database: 	MetaDB  
Release: 	Honeysuckle  
Type: 	Derived table
- - - 
## Description:
Table on agreements_subscription_agreement and resolves values and labels from erm_agreements_refdata_value for: 
* sa_renewal_priority
* sa_is_perpetual
* sa_agreement_status
* sa_reason_for_closure
- - -
## Attributes:
<table>
                <th>Attribut</th>
                <th>Type</th>
                <th>Source - Schema</th>
                <th>Source - Table</th>
                <th>Source - Attribut</th>
                <th>Source - Type</th>
                <th>Source - Multiple values</th>
                <th>Aggregation</th>
                <th>Notes</th>
                <tr>
                    <td>sa_id</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_id</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_renewal_priority</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_renewal_priority</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_renewal_priority_value</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value</td> <!-- Source - Table -->
                    <td>rdv_value</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_renewal_priority_label</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value</td> <!-- Source - Table -->
                    <td>rdv_label</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_is_perpetual</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_is_perpetual</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_is_perpetual_value</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value</td> <!-- Source - Table -->
                    <td>rdv_value</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_is_perpetual_label</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value</td> <!-- Source - Table -->
                    <td>rdv_label</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_name</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_name</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_local_reference</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_local_reference</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td>External sources</td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_agreement_status</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_agreement_status</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_agreement_status_value</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value </td> <!-- Source - Table -->
                    <td>rdv_value</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_agreement_status_label</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value</td> <!-- Source - Table -->
                    <td>rdv_label</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_description</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_description</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_license_note</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_license_note</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_reason_for_closure</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>sa_reason_for_closure</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_reason_for_closure_value</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value</td> <!-- Source - Table -->
                    <td>rdv_value</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_reason_for_closure_label</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>refdata_value</td> <!-- Source - Table -->
                    <td>rdv_label</td> <!-- Source - Attribut -->
                    <td>Varchar</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
                <tr>
                    <td>sa_custom_properties_id</td> <!-- Attribut -->
                    <td>Varchar</td> <!-- Type -->
                    <td>folio_agreements</td> <!-- Source - Schema -->
                    <td>subscription_agreement</td> <!-- Source - Table -->
                    <td>custom_properties_id</td> <!-- Source - Attribut -->
                    <td>Int</td> <!-- Source - Type -->
                    <td>No</td> <!-- Source - Multiple values -->
                    <td>No</td> <!-- Aggregation -->
                    <td></td> <!-- Notes -->
                </tr>
            </table>


## ER-diagram:
```mermaid
        erDiagram
            folio_agreements_subscription_agreement |o..o| folio_agreements_refdata_value : "renewal_priority"
            folio_agreements_subscription_agreement |o..o| folio_agreements_refdata_value : "is_perpetual"
            folio_agreements_subscription_agreement |o..o| folio_agreements_refdata_value : "status"
            folio_agreements_subscription_agreement |o..o| folio_agreements_refdata_value : "reason_for_closure"
                folio_agreements_subscription_agreement {
                    varchar sa_id
                    varchar sa_renewal_priority
                    varchar sa_is_perpetual
                    varchar sa_name
                    varchar sa_local_reference
                    varchar sa_agreement_status
                    varchar sa_description
                    varchar sa_license_note
                    varchar sa_reason_for_closure
                    varchar sa_custom_properties_id
                }
                folio_agreements_refdata_value {
                    varchar sa_renewal_priority_value
                    varchar sa_renewal_priority_label
                    varchar sa_is_perpetual_value
                    varchar sa_is_perpetual_label
                    varchar sa_agreement_status_value
                    varchar sa_agreement_status_label
                    varchar sa_reason_for_closure_value
                    varchar sa_reason_for_closure_label
                }
 ```
