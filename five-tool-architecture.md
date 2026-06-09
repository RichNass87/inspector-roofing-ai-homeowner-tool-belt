# Five-Tool Architecture

The Inspector Roofing AI Homeowner Tool Belt™ works because it treats the homeowner journey as a connected decision chain.

## 1. ScopeReader™

**Gap:** translation.  
**Input:** estimate, scope, line item, supplement, roofing document.  
**Output:** plain-English explanation, terms, missing questions, clarification checklist.  
**Boundary:** educational explanation only.

## 2. Roofmatch™

**Gap:** selection.  
**Input:** style preference, color swipes, manufacturer choices, home aesthetic.  
**Output:** preferred roof color families and manufacturer options.  
**Boundary:** visual discovery only; verify final material availability and exact color.

## 3. Inspector AI Roof Plan Assistant™

**Gap:** planning.  
**Input:** roof concern, urgency, symptoms, photos, documents, address, project type.  
**Output:** inspection prep plan, documentation checklist, rough conversation range, next-step request.  
**Boundary:** does not replace inspection or final quote.

## 4. InstantRoofView™

**Gap:** budgeting.  
**Input:** property address, mapped roof, pitch, waste, obstruction/tree coverage, material tier.  
**Output:** preliminary roof budget preview and downloadable estimate output.  
**Boundary:** final price requires physical verification.

## 5. Inspector AgreementFlow™

**Gap:** execution.  
**Input:** owner/project data, confirmations, signatures, authorization, agreement details.  
**Output:** signed PDF, confirmation ID, audit metadata, submit-back payload.  
**Boundary:** legal review required for production.

## Connected model

```text
Translation -> Planning -> Selection -> Budgeting -> Execution
```

Every tool should connect to a canonical page, schema node, example, glossary entry, video, and safety boundary.
