import "tfconfig"

byte_length = tfconfig.resources.random_id.random.config.byte_length

test_rule = rule { 
    byte_length < 50
}

main = rule {
    test_rule
}
