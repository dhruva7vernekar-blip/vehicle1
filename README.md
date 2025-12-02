if _name_ == "_main_":
    # Sample Output
    vehicle_number = "KA01AB5430"
    owner_name = "dhruv"
    vehicle_type = "Car"
    year_of_manufacture = 2020
    print(vehicle_info(vehicle_number, owner_name, vehicle_type, year_of_manufacture))
    from vehicle import vehicle_info

def test_vehicle_info():
    expected_output = (
        "Vehicle Number: KA01AB1234\n"
        "Owner Name: dhruv\n"
        "Vehicle Type: Car\n"
        "Year of Manufacture: 2020"
    )

    result = vehicle_info("KA01AB1234", "Samarth", "Car", 2020)
    assert result == expected_output
    
