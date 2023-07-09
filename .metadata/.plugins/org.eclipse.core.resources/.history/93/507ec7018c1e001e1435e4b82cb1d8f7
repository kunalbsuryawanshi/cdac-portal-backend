package org.program.repository;

import org.program.entity.FacultyLogin;
import org.springframework.data.jpa.repository.JpaRepository;

public interface FacultyLoginRepository extends JpaRepository<FacultyLogin, Integer>{
	
	public FacultyLogin findByUsernameAndPassword(String username, String password);
}
