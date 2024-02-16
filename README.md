# LayerStructure
Layers {
    DataAccess {
        - Dependencies
        - Models
        - Navigation properties
        - No mappers in DB and mappings
        - Identity Framework
        - Context
    }
    Business {
        - Dependencies
        - DTO (Data Transfer Object)
        - Hubs - Centralizers (SignalR)
        - Interfaces
        - Services
        - Validations
    }
    IO - Input/Output {
        - Dependencies
        - Controlllers
        - Filters
        - Background services
        - Migations
        - wwwroot
        - Host configurations (Development - Production)
        - Class Program.cs - WebHost
    }
    Test {
        - Unit tests
    }
}