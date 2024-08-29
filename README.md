# Technical-task-for-Twoday
Automatiniams testams sukurti buvo naudojama Cypress programa ir Javascript programavimo kalba.
Norint paleisti kodą ir testuoti reikia turėti įrašytą VSC programą, toliau reikia sukurti naują Node.js projektą bei terminale parašyti komandą: npm init -y
Įdiegti Cypress programą terminale parašius eilutę: npm install cypress
Pirmam paleidimui ir projektų kūrimui terminale parašome: npx cypress open
Visų kuriamų automatinių testų pavadinimai turi užsibaigti su galūne "cy.js" jeigu bus naudojama Javascript kalba kaip mano atveju.
Apačioje nurodau savo parašytus 2 automatinius testus pagal duotas sąlygas:



// describe('magento', () => {
    // it('scenario one', () => {
        // Cypress.on('uncaught:exception', (err, runnable) => {  
        //     return false; 
        //   });
    //   cy.visit('https://magento.softwaretestingboard.com/')
    //   cy.get('#ui-id-5 > .ui-menu-icon').trigger('mouseover')
    //   cy.get('#ui-id-17').trigger('mouseover')
    //   cy.get('#ui-id-20').click()
    //   cy.get(':nth-child(3) > #toolbar-amount').contains ('12')
    //   cy.get(':nth-child(5) > .field > .control > #limiter').contains ('12')
    //   cy.get(':nth-child(10) > .product-item-info > .details > .name > .product-item-link').click()
    //   cy.get('#option-label-size-143-item-168').click()
    //   cy.get('#option-label-color-93-item-60').click()
    //   cy.get('#qty').type('2')
    //   cy.get('#product-addtocart-button').click()
    //   cy.get('.showcart > .counter').contains ('12')
    //   cy.get('.showcart').click()
    //   cy.get('.message-success > div > a').click()
    //   cy.wait(2000)
    //   cy.get('.item > .product-item-details > .product-item-name > a').contains('Frankie Sweatshirt')
    //   cy.get('.item-options > :nth-child(2)').contains('M')
    //   cy.get('.item-options > :nth-child(4)').contains('Yellow')
    //   cy.get('.checkout-methods-items > :nth-child(1) > .action').click()
    //   cy.get('#customer-email-fieldset > .required > .control > #customer-email').type('testas@test.com')
    //   cy.get('[name="shippingAddress.firstname"]').type('Test')
    //   cy.get('[name="shippingAddress.lastname"]').type('Testas')
    //   cy.get(':nth-child(2) > ._required > .control').type('Lietuvos 100-50')
    //   cy.get('[name="shippingAddress.city"]').type('Kaunas')
    //   cy.get('select[name="region_id"]').select(2)
    //   cy.get('[name="shippingAddress.postcode"]').type('50505')
    //   cy.get('[name="shippingAddress.telephone"]').type('868687957')
    //   cy.get(':nth-child(1) > :nth-child(1) > .radio').click()
    //   cy.get('.button').click()
    //   cy.get('#billing-address-same-as-shipping-checkmo').click()
    //   cy.get('.payment-method-content > :nth-child(4) > div.primary > .action').click()
    // })
    // })

    // it('scenario two', () => {
    //     cy.visit('https://magento.softwaretestingboard.com/')
    //     cy.get('#ui-id-4').trigger('mouseover')
    //     cy.get('#ui-id-10').trigger('mouseover')
    //     cy.get('#ui-id-15').click()
    //     cy.get(':nth-child(3) > .toolbar-sorter > #sorter').select('Price')
    //     cy.get(':nth-child(1) > .product-item-info > .photo > .product-image-container > .product-image-wrapper > .product-image-photo').click()
    //     cy.get('#option-label-size-143-item-171').click()
    //     cy.get('#option-label-color-93-item-49').click()
    //     cy.get('#product-addtocart-button').click()
    //     cy.get(':nth-child(1) > .product-item-info > .photo > .product-image-container > .product-image-wrapper > .product-image-photo').click()
    //     cy.get('#option-label-size-143-item-171').click()
    //     cy.get('#option-label-color-93-item-50').click()
    //     cy.get('#product-addtocart-button').click()
    //     cy.get(':nth-child(2) > .product-item-info > .photo > .product-image-container > .product-image-wrapper > .product-image-photo').click()
    //     cy.get('#option-label-size-143-item-171').click()
    //     cy.get('#option-label-color-93-item-49').click()
    //     cy.get('#product-addtocart-button').click()
    //     cy.get('.showcart > .counter').contains('3')
    //     cy.get('.message-success > div > a').click()
    //     cy.get(':nth-child(3) > .item-actions > td > .actions-toolbar > .action-delete').click()
    //     cy.get('.checkout-methods-items > :nth-child(1) > .action').click()
    //     cy.visit('https://magento.softwaretestingboard.com/checkout/cart')
    //     cy.get(':nth-child(1) > .product-item-info > .details > .actions > .actions-primary > form > .action').click()
    //     cy.get('.checkout-methods-items > :nth-child(1) > .action').click()
    //       cy.get('#customer-email-fieldset > .required > .control > #customer-email').type('testas@test.com')
    //       cy.get('[name="shippingAddress.firstname"]').type('Test')
    //       cy.get('[name="shippingAddress.lastname"]').type('Testas')
    //       cy.get(':nth-child(2) > ._required > .control').type('Lietuvos 100-50')
    //       cy.get('[name="shippingAddress.city"]').type('Kaunas')
    //       cy.get('select[name="region_id"]').select(2)
    //       cy.get('[name="shippingAddress.postcode"]').type('50505')
    //       cy.get('[name="shippingAddress.telephone"]').type('868687957')
    //       cy.get(':nth-child(1) > :nth-child(1) > .radio').click()
    //       cy.get('.button').click()
    //       cy.get('#billing-address-same-as-shipping-checkmo').click()
    //       cy.get('.payment-method-content > :nth-child(4) > div.primary > .action').click()
    // })
