hello guys i am new to doing cheats and i was wondering if anyone can help me to tell me whats wrong in that code its used to remove shadow and it might be easy but i am new a bit thank you for undrstanding 




void misc::movement::bunny_hop(c_usercmd* cmd) {

	if (variables::test_bool) {
  
		static auto shadows = interfaces::console->get_convar("cl_csm_enabled");
		shadows->set_value(true);
    
	}

};
