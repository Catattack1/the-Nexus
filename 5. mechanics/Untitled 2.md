func get_texture() -> Texture:
    # Return the texture based on the school of magic
    match school:
        "evocation":
            return preload("res://textures/evocation.png")
        "abjuration":
            return preload("res://textures/abjuration.png")
        "transmutation":
            return preload("res://textures/transmutation.png")
        _:
            return preload("res://textures/default.png")