storefront: \
	clean-service-storefront \
	clone-service-storefront

clean-service-storefront:
	rm -rf service-storefront

clone-service-storefront:
	@echo "Cloning service-storefront repository"
	git clone -q ssh://git@jmb.gitlab.schubergphilis.com:2227/microservices/service-storefront.git service-storefront
	-@test "`grep service-storefront .gitignore`" || echo "service-storefront/" >> .gitignore
	@echo "Cloned successfully"