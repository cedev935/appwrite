mutation {
    accountUpdatePassword(
        password: ""
    ) {
        _id
        _createdAt
        _updatedAt
        name
        registration
        status
        passwordUpdate
        email
        phone
        emailVerification
        phoneVerification
        prefs {
            data
        }
    }
}
