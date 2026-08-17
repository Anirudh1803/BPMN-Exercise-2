# Exercise 2 – BPMN Process Modeling using Camunda 8

## Objective

To model different business processes using BPMN (Business Process Model and Notation) in Camunda 8 Modeler.

## Tool Used

* Camunda 8 Modeler
* BPMN 2.0

## 1. Hotel Room Reservation

This process models an online hotel room booking.

### Process Flow

1. Guest submits a room booking request.
2. The system checks room availability.
3. If rooms are unavailable, the guest is notified and the process ends.
4. If rooms are available, payment is requested.
5. If payment is successful, the booking is confirmed and a booking reference is generated.
6. If payment fails, the guest is notified and the process ends.
7. A booking confirmation email is sent to the guest.
8. The process ends.

## 2. Loan Application Processing

This process models the processing of a personal loan application at a bank.

### Process Flow

1. Customer submits a loan application.
2. The bank verifies the applicant's documents and credit score.
3. If the documents are incomplete or invalid, the application is rejected and the customer is notified.
4. If the documents are valid, the applicant's eligibility is checked.
5. If the applicant is not eligible, a rejection notification is sent.
6. If the applicant is eligible, the application is forwarded to the loan officer.
7. The loan officer makes the final approval decision.
8. If approved, the loan amount is disbursed and an approval notification is sent.
9. If rejected, a rejection notification is sent.
10. The process ends.

## 3. Job Applicant Recruitment Process

This process models the recruitment process for a job application received by an HR department.

### Process Flow

1. Candidate submits a job application online.
2. The HR system screens the application against the minimum eligibility criteria.
3. If the candidate is not eligible, a rejection notification is sent and the process ends.
4. If eligible, a technical interview is scheduled.
5. The technical panel evaluates the candidate's performance.
6. If the candidate fails the technical interview, a rejection notification is sent.
7. If the candidate passes, an HR/managerial round is scheduled.
8. If the candidate is rejected in the HR round, a rejection notification is sent.
9. If selected, an offer letter is generated and sent to the candidate.
10. The process ends.

## BPMN Elements Used

* Start Event
* Tasks
* Exclusive Gateways
* Sequence Flows
* Alternative Paths
* End Events

## Conclusion

The three business processes were successfully modeled using BPMN in Camunda 8 Modeler. Exclusive gateways were used to represent decision points and alternative process paths.
