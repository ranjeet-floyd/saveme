# Basic Table schema
    ## User Profile
        ID
        Title
        FirstName
        MiddleName
        LastName
        Gender
        Mobile
        Email
        CreateDateTime
        UpdatedDateTime
        UserType -> user/passenger

    ## User Login
        ID
        LoginId
        Pwd
        ProfileId  -> # User Profile
        LastLoginDateTime
    
    ## Flight Ticket
        ID
        FlightDateTime
        FromLocation
        ToLocation
        FlightPNR
        FlightCarrier
        Passengers  -> # User Profile

    
        

        

        
